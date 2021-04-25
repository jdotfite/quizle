<template>
  <b-container>
    <h1>Hello, Bootstrap-Vue</h1>
    <b-btn 
      variant="primary"
      @click="showAlert = true"
    >
      Click
    </b-btn>
    <b-alert 
      v-bind:show="showAlert"
      variant="success"
    >
      You clicked the button!
    </b-alert>
  </b-container>
</template>
<script>
export default {
  data: () => ({
    showAlert: false
  })
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
