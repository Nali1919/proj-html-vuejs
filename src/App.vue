<template>
  <div id="app">
    <HeaderComponent :Citta='ArrayCitta' />
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
  font-family: 'Roboto', 'Sans-Serif';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

@import url('https://fonts.googleapis.com/css2? family= Poppins:wght@600 & family= Roboto:ital,wght@0,300;1,300 & display=swap');


* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  overflow-x: hidden;

}
</style>
