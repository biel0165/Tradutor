<script setup>
import { ref } from 'vue'
const idioma = ref("Olá mundo!")

function Ingles() {
  idioma.value = "Hello World!"
}
function Espanhol() {
  idioma.value = "Hola Mundo!"
}
function Italiano() {
  idioma.value = "Ciao Mondo!"
}
function Russo() {
  idioma.value = "Привет, мир!"
}
function Tcheco() {
  idioma.value = "Ahoj světe!"
}
function Portugues() {
  idioma.value = "Olá Mundo!"
}
function Frances() {
  idioma.value = "Bonjour le monde"
}





</script>

<template>
  <h1>{{ idioma }}</h1>
  <button v-on:click= "Ingles">Inglês</button>
  <button v-on:click= "Espanhol">Espanhol</button>
  <button v-on:click= "Italiano">Italiano</button>
  <button v-on:click= "Russo">Russo</button>
  <button v-on:click= "Tcheco">Tcheco</button>
  <button v-on:click= "Portugues">Português</button>
  <button v-on:click= "Frances">Francês</button>
</template>

<style scoped>

</style>
