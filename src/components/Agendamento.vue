<template>
  <div class="modal-bg">
    <div class="modal-content">
      <button class="close-modal" @click="$emit('close')">×</button>
      <h2>Agende seu horário</h2>
      <form @submit.prevent="confirmar">
        <input type="text" placeholder="Nome" v-model="nome" required />
        <input type="email" placeholder="E-mail" v-model="email" required />
        <input type="datetime-local" v-model="datahora" required />
        <button type="submit">Confirmar</button>
      </form>
      <div v-if="msg" class="sucesso">{{ msg }}</div>
    </div>
  </div>
</template>
<script setup>
import { ref } from 'vue'
const nome = ref('')
const email = ref('')
const datahora = ref('')
const msg = ref('')
function confirmar() {
  msg.value = 'Agendamento registrado com sucesso!'
  setTimeout(() => msg.value = '', 2500)
}
</script>
<style scoped>
.modal-bg {
  position: fixed; top: 0; left: 0; width: 100vw; height: 100vh;
  background: rgba(0,0,0,0.65);
  display: flex; align-items: center; justify-content: center;
  z-index: 99;
}
.modal-content {
  background: #222;
  color: #fff;
  padding: 32px 24px;
  border-radius: 12px;
  min-width: 320px; max-width: 350px;
  position: relative;
}
.close-modal {
  position: absolute; top: 12px; right: 14px; background: none; border: none;
  color: #DC143C; font-size: 2rem; cursor: pointer;
}
input, button {
  display: block; width: 100%; margin: 12px 0; padding: 10px;
  border-radius: 6px; border: 1px solid #444; background: #181818; color: #fff;
}
button {
  background: #DC143C; color: #fff; font-weight: bold; border: none;
}
.sucesso { color: #1af720; margin-top: 16px; font-weight: bold; }
</style>
