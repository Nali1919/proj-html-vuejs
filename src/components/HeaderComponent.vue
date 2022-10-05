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


  

      <div class="ggs">
      <img class="img-svg" src="../assets/img/svg-1.svg" alt="">
      <span>Cart</span>
      
      </div>

      <div class="img-pizza1">
        <img class="img-pizza" src="../assets/img/h3-rev-img-6.png" alt="">
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
  height: 400px;
  display: flex;
  justify-content: space-around;
  padding: 40px;
  position: relative;
 }
 .ac-row{
max-width: 1200px;
margin: 0 auto;
 }
 .ac-button{
width: 100px;
background-color: orange;
color: white;
border: 0;
padding: 1px;
cursor: pointer;
 }
 .img-svg{
  background-color:  white;
 }
 span,a{
  color: white;
  text-decoration: none;
 }
 .navbar-menu{
  display: flex;
  column-gap: 20px;
  padding: 3px;
 }
 .don-peppe-img{
  width: 100px;
  position: relative;
  bottom: 30px
 }
 .img-pizza{
width: 200px;
position: absolute;
right: 610px;
top: 100px;
 }
 .ggs{
display: flex;
align-items: center;
column-gap: 5px;
position: relative;
bottom: 148px;

 }



</style>