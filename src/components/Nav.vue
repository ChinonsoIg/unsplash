<template>
  <div id="nav">
    <input 
      v-model="search"
      placeholder="Search for photo"
    >
  </div>
</template>

<script>
export default {
  name: 'Nav',
  props: {
    search: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#nav {
  height: 180px;
  display: grid;
  place-items: center;
  background-color: rgba(0, 128, 128, 0.1);
}
input {
  height: 30px;
  width: 80%;
  border: none;
  padding: 5px 10px;
  border-radius: 8px;
}

@media (max-width: 575.98px) {
  .nav {
  height: 120px;
}
input {
  width: 90%;
  padding: 2px 5px;
  border-radius: 5px;
}
}
</style>
