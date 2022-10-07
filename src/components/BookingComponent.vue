<template>
  <div class="Input-container">
<div><button>
   <div class="flex">
    <div>1 Person</div>
    <div><i class="fa-solid fa-user-group"></i></div>
   </div>
</button>
<span>FOR</span>
</div>
<div><button>
   <div class="flex">
    <div>11/29/2020</div>
    <div><i class="fa-solid fa-calendar"></i></div>
   </div>
</button>
<span>AT</span>
</div>
<div><button>
   <div class="flex">
    <div>7:00 pm</div>
    <div><i class="fa-solid fa-bell"></i></div>
   </div>
</button>


</div>
<div><button class="ordina">BOOK A TABLE</button></div>


  </div>
</template>

<script>
export default {
name: 'BookingComponent'

}
</script>

<style lang="scss" scoped>
.Input-container{
margin-top: 10px;
background-image: url(../assets/img/h3-background-img-3.jpg);
background-size: cover;
background-position: center;
height: 200px;
display: flex;
justify-content: center;
align-items: center;
column-gap: 50px;
}
button{
width: 200px;
padding: 10px;
cursor: text;
}
span{
color: white;
margin-left: 40px;
}
.flex{
display: flex;
justify-content: space-between;
}
.ordina{
 width: 200px;
padding: 10px;   
color: white;
background-color: orange;
cursor: pointer;
}

.fa-user-group,.fa-calendar,.fa-bell  {
color: orange;
font-size: 15px;
}
</style>