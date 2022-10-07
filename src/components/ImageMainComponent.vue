<template>
  <div class="ac-container my-1">
    <div class="ac-row ">
        <div class="col img-1">
            <img  src="../assets/img/h3-img-1.jpg" alt="">
            <div class="hidden-menu">
                <i class="fa-solid fa-eye"></i>
            </div>
        </div>
        <div class="col img-2">
            <img  src="../assets/img/h3-img-2.jpg" alt="">
            <div class="hidden-menu">
                <i class="fa-solid fa-eye"></i>
            </div>
        </div>
        <div class="col img-3">
            <img  src="../assets/img/h3-img-3.jpg" alt="">
            <div class="hidden-menu">
                <i class="fa-solid fa-eye"></i>
            </div>
        </div>
        <div class="col img-4">
            <img src="../assets/img/h3-img-4.jpg" alt="">
            <div class="hidden-menu">
                <i class="fa-solid fa-eye"></i>
            </div>
        </div>

    </div>

  </div>
</template>

<script>
export default {
name: 'ImageMainComponent'

}
</script>

<style lang="scss" scoped>
.ac-container img{
    width: 100%;
}
.ac-row{
    display: flex;
    column-gap: 2px;
}
.img-1, .img-2, .img-3, .img-4{
position: relative;
overflow-y: hidden;
}
.hidden-menu{
display: flex;
justify-content: center;
align-items: center;
width: 350px;
height: 222px;
background-color: white;
position: absolute;
top: 0;
left: 0;
right: 0;
bottom: 0;
margin: auto;
opacity: 0;
}
.img-1:hover .hidden-menu{
opacity: 1;
}
.img-2:hover .hidden-menu{
opacity: 1;
}
.img-3:hover .hidden-menu{
opacity: 1;
}
.img-4:hover .hidden-menu{
opacity: 1;
}

.fa-eye{
color: white;
background-color: red;
width: 50px;
border-radius: 50%;
}


</style>