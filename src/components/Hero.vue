<template>

  <section>
    <h2>The Heroes</h2>
  </section>
  
</template>

<script>
export default {
  name: 'Hero'
}
</script>

<style scoped>

  section {
    width: 100%;
    height: 800px;
    padding: 20px 10%;
    background-image: url('../assets/heroes.jpeg');
    background-size: contain;
  }

  h2 {
    color: #FFF;
    font-size: 50px;
    text-align: left;
    margin-left: 20px;
  }

</style>