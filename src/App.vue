<script setup>
import { ref } from 'vue'
const idioma = ref("Olá Mundo!")

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
function Noruegues() {
  idioma.value = "Hei verden!"
}
function Frances() {
  idioma.value = "Bonjour le monde!"
}
function Mandarim() {
  idioma.value = "你好世界"
}
function Alemao() {
  idioma.value = "Hallo Welt!"
}
function Portugues() {
  idioma.value = "Olá Mundo!"
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
  <button v-on:click= "mandarim">Mandarim</button>
  <button v-on:click= "alemao">Alemão</button>
  <button v-on:click= "Noruegues">Norueguês</button>
</template>

<style scoped>

</style>
