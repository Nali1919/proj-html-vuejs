<template>
  <div class="ac-container">
    <div class="row">
        <div class="col-6 relative">
            <img class="img-relative" src="../assets/img/h1-img-4.jpg" alt="">
           <div><img class="img-white" src="../assets/img/h1-img-7n.png" alt=""></div>
        </div>
        <div class="col-6 ac-price ">
             <h1>Specials*</h1>
             <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Omnis neque deleniti tempore</p> 

             <div>
                <span><strong>$10</strong> COMBO PICCOLO</span>
                <p class="kk"> Lorem ipsum dolor sit amet consectetur adipisicing elit. Dicta quibusdam dolor expe</p>
             </div>
               <div>
                <span> <strong>$20</strong> COMBO MEZZO</span>
                <p class="kk"> Lorem ipsum dolor sit amet consectetur adipisicing elit. Dicta quibusdam dolor expe</p>
             </div>
               <div>
                <span> <strong>$30</strong> COMBO GRANDE</span>
                <p class="kk"> Lorem ipsum dolor sit amet consectetur adipisicing elit. Dicta quibusdam dolor expe</p>
             </div>

        </div>  
    </div>
  </div>
</template>

<script>
export default {
name: 'PriceComponent'

}
</script>

<style lang="scss" scoped>

.ac-price{
max-width: 400px;
margin: 0 auto;
margin-top: 100px;
}
.kk{
position: relative;
left: 30px;
}
strong{
    color: red;
}
.img-white{
position: absolute;
width: 200px;
bottom: 180px;
left: 220px;

}
.img-relative{
width: 100%;
}
.relative{
position: relative;
}


</style>