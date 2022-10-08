<template>
  <div id="app">
 <HeaderComponent :Citta='ArrayCitta'/>
 <MainComponent />
 <FooterComponent />

    </div>
 
</template>

<script>
import HeaderComponent from './components/HeaderComponent'
import MainComponent from './components/MainComponent.vue';
import FooterComponent from './components/FooterComponent.vue';




export default {
  name: 'App',
  components: {
    HeaderComponent,
    MainComponent,
    FooterComponent
},
data() {
  return {
    ArrayCitta: [
      {
        citta: 'Salerno',
      ristorante: 'PizzaSuper'
      },
       {
         citta: 'Napoli',
        ristorante: 'Sorbillo'
      },
        {
          citta: 'Palermo',
        ristorante: 'TheSudPizza'
       },
        {
          citta: 'Bari',
        ristorante: 'RossoPomodoro'
       },
       
    
   ]
    
    
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
  overflow-x: hidden;
  
}




</style>
