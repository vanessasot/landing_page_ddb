<template>
  <div id="app">
    <Modal ref="modal">
      <p>Hello World!</p>
    </Modal>
    <router-view/>
  </div>
</template>

<script>

import Modal from './components/Modal.vue'
import HomePage from './components/HomePage.vue'

export default {
  name: 'App',
  components: {
    Modal,
    HomePage
  },
  methods: {
    openModal () {
      const modal = document.getElementById('modal')
      modal.classList.add('show')
    }
  }
}
</script>

<style>
#app {
  font-family: 'Barlow', 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #161616;
}
</style>
