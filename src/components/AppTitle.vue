<template>
  <div>
    <h1>{{primoTitolo}}</h1>
  </div>
</template>

<script>
export default {
  
  data() {
    return {
      primoTitolo : "La mia prima app con Vite!"
    }
  },

}
</script>

<style>
h1{
  text-align: center;
  color: red;
  padding-top: 2rem;
}
</style>