<template>
  <div>
    <img :src="srcImmagine" alt="uomo con la bici in campagna">
  </div>
</template>

<script>
export default {
  
  data() {
    return {
      
      srcImmagine : "https://redazione-style.corriere.it/wp-content/uploads/2020/05/bici-pexels.jpg"

    }
  },
}
</script>

<style>
img{
  display: block;
  width: 100%;
}
</style>

