<template>
<div :class="[clase]">
  <input @click="cambioBackground" type="button" value="presiona este boton">
  <NavBar />
    <Suma />
    <Loop />
    <Boolean />
    <Footer />
</div>



</template>
<script setup>

import NavBar from "./components/NavBar.vue"
import Boolean from "./components/Boolean.vue"
import Suma from "./components/Suma.vue"
import Footer from "./components/Footer.vue"
import Loop from "./components/Loop.vue"
import { ref } from 'vue'



const clase = ref("white")
function cambioBackground() { 
  console.log(clase.value)
  clase.value= "black"}

</script>



<style scoped>

.white{
  background-color: white;
}

.black{
  background-color: black;
}
</style>