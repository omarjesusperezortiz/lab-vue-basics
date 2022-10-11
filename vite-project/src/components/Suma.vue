<template>

<div class="section">
<p>El resultado de 2+2 es: {{operation}}</p>

<p>El resultado de 2+2 es: {{ suma }}</p>

<button @click="sumatoria">Muestra el resultado de 2+2 </button>
</div>
</template>


<script setup>
import { ref } from 'vue'
const operation = 2+2

const suma = ref("...")



function sumatoria() { suma.value = 4}

</script>

<style scoped>
</style>