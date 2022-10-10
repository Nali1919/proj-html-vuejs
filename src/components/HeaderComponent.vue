<template>
  <div class="ac-container">
    <div class="navbar">
      <div><button>Order Online</button></div>
      <div class="link-menu">
        <img class="baffo" src="../assets/img/svg-0.svg" alt="">
        <a href="">HOME</a>

        <a href="">PAGES</a>
        <a href="">MENU</a>
        <img class="don-peppe-img" src="../assets/img/h5-logo-divided-header.png" alt="">
        <a href="">EVNET</a>
        <a href="">BLOG</a>
        <a href="">LANDING</a>
      </div>

      <div class="terza-section">
        <div class="consegna">
          <img class="delivery" src="../assets/img/svg-1.svg" alt="">
          <span>CART</span>
        </div>
        <div class="cerca">
          <i class="fa-solid fa-magnifying-glass"></i>
          <span>SEARCH</span>
        </div>
      </div>




    </div>
    <img class="urban" src="../assets/img/h3-rev-img-5.png" alt="">
    <img class="pizza" src="../assets/img/h3-rev-img-6.png" alt="">


    <div class="restaurant">
      <div class="title">
        <h5>Sedi Urban:</h5>
      </div>
      <div v-for="city in Citta" :key="city.ristorante">
        <div class="flex">
          {{city.citta}}:
          {{city.ristorante}}


        </div>

      </div>
    </div>




  </div>
</template>

<script>
export default {
  name: 'HeaderComponent',
  props: {
    Citta: Array
  }


}


</script>

<style lang="scss" scoped>
.ac-container {
  background-image: url(../assets/img/background-img-header.png);
  height: 450px;
  position: relative;
}

.urban {
  width: 500px;
  position: absolute;
  margin: auto;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
}

.pizza {
  width: 200px;
  position: absolute;
  margin: auto;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
}

.navbar {
  display: flex;
  justify-content: space-evenly;
  align-items: flex-start;
  padding: 30px;
  margin-left: 50px;

}

button {
  color: white;
  background-color: orange;
  border: 0;
  padding: 5px;
  font-size: 10px;
}

.link-menu {
  display: flex;
  align-items: flex-start;
  column-gap: 20px;
}

.don-peppe-img {
  width: 70px;
}

a,
span {
  text-decoration: none;
  font-size: 10px;
  color: white;
}

.baffo {
  display: inline;
  width: 15px;
  position: relative;
  left: 18px;
  top: 1px;
}

.delivery {
  width: 20px;
  position: relative;
  bottom: 2px;
}

.consegna {
  display: flex;
  align-items: flex-start;
  column-gap: 5px;
}

.cerca {
  display: flex;
  align-items: flex-start;
  column-gap: 5px;
}

.fa-magnifying-glass {
  color: white;
  font-size: 12px;
}

.terza-section {
  display: flex;
  column-gap: 15px;
}

.flex {
  display: flex;
  color: white;
  padding: 10px;

}

.title {
  color: red;
  padding: 10px;
}

.restaurant {
  display: flex;
  justify-content: center;
  padding-top: 300px;
}
</style>