<template>
  <div class="ac-container ">
      <div>
        <button class="ac-button">Order Online</button>
      </div>


      <div class="navbar-menu"> 
        <a href="">HOME</a>
        <a href="">PAGES</a>
        <a href="">MENU</a>
        <a href="">
          <img class="don-peppe-img" src="../assets/img/h5-logo-divided-header.png" alt="">
        </a>
        <a href="">EVENT</a>
        <a href="">BLOG</a>
        <a href="">LANDING</a>
      </div>


  

      <div>
      <img class="img-svg" src="../assets/img/svg-1.svg" alt="">
      <span>Cart</span>
      
      </div>
  </div>
</template>

<script>
export default {
  name: 'HeaderComponent',


}


</script>

<style lang="scss" scoped>
 
 .ac-container{
background-color: black;
  background-image: url(../assets/img/h3-rev-img-5.png);
  height: 250px;
  display: flex;
  justify-content: space-evenly;
  padding: 40px;
 }
 .ac-row{
max-width: 1200px;
margin: 0 auto;
 }
 .ac-button{
width: 120px;
background-color: red;
 }
 .img-svg{
  background-color:  white;
 }
 span,a{
  color: white;
 }
 .navbar-menu{
  display: flex;
  column-gap: 20px;;
 }
 .don-peppe-img{
  width: 100px;
  position: relative;
  bottom: 30px
 }




</style>