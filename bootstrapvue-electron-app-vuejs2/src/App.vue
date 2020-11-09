<template>
  <b-container>
    <p>Hello, Bootstrap-Vue</p>
    <p>https://vuejsdevelopers.com/2020/07/29/bootstrap-vue/</p>
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

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
