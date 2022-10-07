<template>
<div class="container-ac">
 <div class="row-ac">
   <div class="img-left">
     <div class="flex-column">
        <h6>FIND OUR RESTAURANTS</h6>
        <div class="column">
         <span>1614 E.Bel Rd #104s</span>
         <span>Salerno, AZ 85022</span>
         <span>(602)867-1010</span>
        </div>
        <div class="column">
         <span>1614 E.Bel Rd #104s</span>
         <span>Salerno, AZ 85022</span>
         <span>(602)867-1010</span>
        </div>
        <div class="column">
         <span>1614 E.Bel Rd #104s</span>
         <span>Salerno, AZ 85022</span>
         <span>(602)867-1010</span>
        </div>
        <div class="column">
         <span>1614 E.Bel Rd #104s</span>
         <span>Salerno, AZ 85022</span>
         <span>(602)867-1010</span>
        </div>
      </div>
       <div class="flex-column">
        <h6>WORKING HOURS</h6>
        <div class="column">
        <span class="orange">MONDAY</span>
        <span class="red">KITCHEN CLOSED</span>
        </div>
        <div class="column">
        <span class="orange">TUESDAY UNTIL FRIDAY</span>
        <span>9:00-22:00</span>
        </div>
      <div class="column">
        <span class="orange">Saturday <strong class="red">*</strong></span>
        <span>Saturday 11am to midnight</span>
        </div>
        <div class="column">
        <span class="orange">SUNDAY</span>
        <span class="red">9:00-22:00</span>
        </div>
        <div class="social">
        <div class="icon">
           <span class="orange">FOLLOW US:</span>
          <span class="white"><i class="fa-brands fa-twitter"></i> </span> 
           <span class="white"> <i class="fa-brands fa-facebook-f"></i> </span>
            <span class="white"> <i class="fa-brands fa-instagram"></i>  </span> 
            <span class="white"> <i class="fa-brands fa-linkedin-in"></i> </span> 
        </div>
       </div>
      </div>
      <div class="text">
        <h4>THE DON PEPPE CREW 
            FIRST AND FIREMOST
            VALUES AN AUTHENTIC
            WELL BAKED SLICE OF
            PIZZA
        </h4>
      </div>
      
     </div>
     <div class="img-right">
       

     </div>

    </div>
    
  </div>
</template>

<script>
export default {
name: 'FooterComponent'

}
</script>

<style lang="scss" scoped>
.container-ac{
margin-top: 10px;
}
.row-ac{
display: flex;
}
.img-left{
background-image: url(../assets/img/background-img-header.png);
width: 50%;
display: flex;
column-gap: 20px;
padding: 20px;
padding: 50px;


}

.img-right{
background-image: url(../assets/img/footer-img-1.jpg);
background-size: cover;
background-position: center;
width: 50%;
height: 500px;
}
.flex-column{
display: flex;
flex-direction: column;

}
h6{
color: orange;
font-size: 10px;
}
span{
color: gray;
font-size: 10px;
}
h4{
color: white;
font-size: 18px;
}
.text{
width: 250px;
}
.column{
display: flex;
flex-direction: column;
margin-bottom: 10px;
}
.red{
color: red
}
.orange{
color: orange;
}
.icon{
display: flex;
column-gap: 10px;
}
.white{
color: white;
}
</style>