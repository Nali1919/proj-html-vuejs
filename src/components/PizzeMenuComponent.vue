<template>
    <div>
        <div class="container-ac">
          <div class="row text-center py-5">
               <div class="col-12"><span>Chose your flavor</span></div>
             <div class="col-12"> <h3>THE BEST PIZZA MENU IN TOWN</h3></div>
              <div class="col-12"> <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptate distinctio ab ad dicta at explicabo </p></div>  
           </div>
        </div> 
        <div class="container-pizze">
            <div class="row-ac">
    <div class="col text-center bismark-position">
        <img class="bismark" src="../assets/img/h3-product-img-1a-100x100.png" alt="">  
        <h6>Bismark</h6>
        <span><s>$35</s> 30$s</span>

    </div> 
     <div class="col text-center fior-position ">
        <img src="../assets/img/h3-product-img-2a-150x150.png" alt=""> 
        <h6>Fior di Zucca</h6>
        <span>$7-$50</span>
    
    
    </div> 
     <div class="col text-center valdostana-position">
        <img src="../assets/img/h3-product-img-3a-150x150.png" alt="">
        <h6>Valdostana</h6> 
        <span>$55.50</span>
    
    
    </div> 
     <div class="col text-center tartufata-position">
        <img src="../assets/img/h3-product-img-4a-150x150.png" alt="">
        <h6>Pizza Tartufata</h6> 
        <span>$45.50</span>
    
    </div> 
     <div class="col text-center francescana-position">
        <img src="../assets/img/h3-product-img-5a-150x150.png" alt="">  
        <h6>Francescana</h6>
        <span>$25.00</span>
    
    </div> 
     <div class="col text-center campagnola-position">
        <img class="campagnola" src="../assets/img/h3-product-img-6a-100x100.png" alt="">
        <h6>Campagnola</h6> 
        <span>$50.00-$95.00</span>
    
    </div> 
            </div>
        </div>
    </div>

   
    

</template>

<script>
export default {
name: 'PizzeMenuComponent.vue'

}
</script>

<style lang="scss" scoped>
span{
color: red;
}
h6{
color: orange;
}
.bismark{
width: 150px;
height: 150px;
}
.bismark-position{
position: relative;
right: 80px;
}
.fior-position{
    position: relative;
    right: 80px;
}
.valdostana-position{
position: relative;
right: 50px;
}
.francescana-position{
position: relative;
left: 50px;
}
.tartufata-position{
position: relative;
left: 10px;
}

.campagnola{
width: 150px;
height: 150px;  
}
.campagnola-position{
    position: relative;
    left: 80px;
}
s{
color: gray;
}

.row-ac{
width: 100%;
display: flex;
margin: 0;
}
.container-pizee{
width: 100%;
margin: 0 
}
.container-ac{
max-width: 500px;
margin: 0 auto;
}





</style>