<template>
  <div id="app">
 <HeaderComponent/>
 <MainComponent />

    </div>
 
</template>

<script>
import HeaderComponent from './components/HeaderComponent'
import MainComponent from './components/MainComponent.vue';




export default {
  name: 'App',
  components: {
    HeaderComponent,
    MainComponent
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
