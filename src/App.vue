<template>
  <Header />
  <Home @open-agendar="showModal = true"/>
  <Agendamento v-if="showModal" @close="showModal = false"/>
</template>
<script setup>
import { ref } from 'vue'
import Header from './components/Header.vue'
import Home from './views/Home.vue'
import Agendamento from './components/Agendamento.vue'
const showModal = ref(false)
</script>
