<template>

<div class="container-ac">
    <div class="row-ac">
        <div class=" img-left">
         <div class="flex-title">
            <span>Made with love</span>
             <h2>Delish Pizza Deals</h2> 
         </div>

         <div class="flex-date">
          <div class="column">
            <h3>02</h3>
            <h4>NOV</h4>
          </div>
          <div class="flex-location">
            <h5>TRADITIONAL NEAPOLITAN PIES IN KYOTO PIZZA MERCATO</h5>
            <span><i class="fa-solid fa-location-dot"></i> 204 E.Pizzetta Tommaso </span>
          </div>
         </div>
         <hr>
         <div class="flex-date">
          <div class="column">
            <h3>03</h3>
            <h4>NOV</h4>
          </div>
          <div class="flex-location">
            <h5>TERARAZZA PATIO DINING SPACE OPENING THIS WEEKEND</h5>
            <span><i class="fa-solid fa-location-dot"></i> 204 E.Pizzetta Tommaso</span>
          </div>
         </div>
         <hr>
         <div class="flex-date">
          <div class="column">
            <h3>05</h3>
            <h4>NOV</h4>
          </div>
          <div class="flex-location">
            <h5>SIENNA PRIVATE DINING ROOM WITH STEPHANE BRUNN</h5>
            <span><i class="fa-solid fa-location-dot"></i> 204 E.Pizzetta Tommaso</span>
          </div>
         </div>
         


            
        </div>
        <div class=" img-right">


        </div>

    </div>

</div>
  
</template>

<script>
export default {
name : 'EventComponent'

}
</script>

<style lang="scss" scoped>
.container-ac{
margin-top: 50px;
}
.img-left{
background-image: url(../assets/img/background-img-header.png);
height: 600px;
padding: 50px;
width: 50%;

}
.img-right{
background-image: url(../assets/img/h3-img-5a.jpg);
background-position: center;
background-size: cover;
width: 50%;
height: 700px;
}
.row-ac{
display: flex;

}
.flex-title{
display: flex;
flex-direction: column;
align-items: flex-start;
}

span,h3{
color: red;
}

h2,p,h5,h4{
color: white;
}
h5{
font-size: 15px;
}

.column{
display: flex;
flex-direction: column;
}
.flex-date{
display: flex;
align-items: center;
column-gap: 10px;
margin-top: 20px;
}
.flex-location{
display: flex;
flex-direction: column;
row-gap: 2px;
align-items: baseline;
}
hr{
color: orange;
width: 85%;
border: 1px dashed orange;
}



</style>