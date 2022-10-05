<template>
  <div id="app">
 <HeaderComponent/>

    </div>
 
</template>

<script>
import HeaderComponent from './components/HeaderComponent'




export default {
  name: 'App',
  components: {
  HeaderComponent

  },
data() {
  return {
    
    
  }
}
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}




</style>
