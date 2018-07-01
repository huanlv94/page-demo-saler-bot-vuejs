<template>
  <div id="app">
    <img src="./assets/logo.png">
    <demo-sale-popup></demo-sale-popup>
  </div>
</template>

<script>
import demoSalePopup2 from 'demo-sale-popup2'
export default {
  components: {
    'demo-sale-popup': demoSalePopup2
  },
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
