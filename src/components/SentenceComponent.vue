<template>
<div class="container-back">
    <div class="ac-container">
    <div class="row">
        <div class="col-12 text-center">
             <h4><i class="fa-solid fa-quote-left"></i></h4>
                <h5 class="sentence-pizza">
                ''FORGET THE TRENDY PIZZA SHOP, THE HIDDEN SPOT MAKES THE BEST NEW YORK-STYLE PIZZA SLICE IN NAPLES?'' 
                  </h5>
                <p>Washington post in 2019</p>
        </div>
    </div>
    </div>


</div>
  
  

</template>

<script>
export default {
name: 'SentenceComponent'

}
</script>

<style lang="scss" scoped>
    .ac-container{
        height: 400px;
        max-width: 1000px;
        margin: 0 300px;
        padding-top: 100px;
    }
    .container-back{
         background-image: url(../assets/img/h3-testimonials-bckgrnd.jpg);
        background-size: cover;
        background-position: center;
    }
   
    .fa-quote-left{
    color: orangered;
    font-size: 70px;
    }

</style>