<template>
  <div class="grid-container">
    <div class="grid-item">1</div>
    <div class="grid-item">2</div>
    <div class="grid-item">3</div>
    <div class="grid-item">4</div>
    <div class="grid-item">5</div>
    <div class="grid-item">6</div>
  </div>
</template>

<script>
export default {
  name: 'LandingPage',
  // props: {
  //   msg: String
  // }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.grid-container {
  position: relative;
  top: -40px;
  margin: 0 auto;
  display: grid;
  grid-auto-rows: 5rem;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  grid-gap: 50px;
  max-width: 800px;
  /* border: 1px solid red; */
}

.grid-item {
  background-color: teal;
  text-align: center;
  color: white;
  border-radius: 10px;
  font-size: 24px;
  text-align: center;
}
</style>
