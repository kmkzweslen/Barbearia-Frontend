<template>
  <main>
    <Hero />
    <SobreMarca />
    <Equipe />
    <section class="agendamento-sec">
      <div>
        <h2>Faça já o seu agendamento</h2>
        <button @click="$emit('open-agendar')" class="btn-agendar">AGENDAR</button>
      </div>
      <ServicosPlaceholders />
    </section>
  </main>
</template>
<script setup>
import Hero from '../components/Hero.vue'
import SobreMarca from '../components/SobreMarca.vue'

import ServicosPlaceholders from '../components/ServicosPlaceholders.vue'
</script>
<style scoped>
.agendamento-sec {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background: #1a1a1a;
  padding: 40px 0;
  color: #fff;
}
.btn-agendar {
  background: #DC143C;
  color: #fff;
  border: none;
  padding: 16px 32px;
  font-weight: 700;
  cursor: pointer;
  border-radius: 6px;
  font-size: 1rem;
}
</style>
