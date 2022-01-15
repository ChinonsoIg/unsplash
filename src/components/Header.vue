<template>
  <div id="header">
    <form>
      <input 
        v-model="search"
        placeholder="Search for photo"
      >
    </form>
  </div>
</template>

<script>
export default {
  name: 'Header',
  props: {
    search: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#header {
  height: 180px;
  display: grid;
  place-items: center;
  background-color: rgba(0, 128, 128, 0.1);
  width: 100%;
}
form {
  width: 80%;
  margin: 0 auto;
  background: gray;
  text-align: left;
  padding: 0;
  border-radius: 10px;
  /* border: 2px solid red; */
}
input {
  display: block;
  width: 100%;
  padding: 10px 6px;
  font-size: 16px;
  border-radius: 10px;
  box-sizing: border-box;
  border: none;
}

@media (max-width: 575.98px) {
  .header {
    height: 120px;
  }
  form {
    width: 90%;
    padding: 2px 5px;
    border-radius: 5px;
  }
}
</style>
