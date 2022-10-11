<template>

    <div class="section">
        
        <li v-for="(value, key) in myObject">
        {{ key }}: {{ value }}
        </li>
            </div>

</template>
<script >
export default {
data() {
  return {
    myObject: {
      title: 'How to do lists in Vue',
      Description: 'Dudado',
      Content: 'Lorem ipsum Loremp loremroamsdomerapmeaprmpae'
    }
  }
}
}
</script>
<style scoped>
</style>