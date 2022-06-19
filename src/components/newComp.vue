<template>
  <div id="full-width-container">
    <h1>Hover Board with the Kids</h1>
    <img id="board" v-bind:src="require('../assets/skateboard.png')" />
  </div>
</template>

<script>
export default {
  name: "newComp",
  props: {
    text: String,
  },
};
</script>

<style scoped>
#full-width-container {
  width: 100vw;
  height: 100vh;
  background-color: white;
  display: flex;
  justify-content: center;
}
.colored {
  border: 5px;
  border-color: black;
  background-color: grey;
}

#board {
  width: 40%;
  height: auto;
}
</style>
