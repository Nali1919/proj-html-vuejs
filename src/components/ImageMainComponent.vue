<template>
  <div class="ac-container my-1">
    <div class="ac-row ">
        <div class="col">
            <img  src="../assets/img/h3-img-1.jpg" alt="">
        </div>
        <div class="col">
            <img  src="../assets/img/h3-img-2.jpg" alt="">
        </div>
        <div class="col">
            <img  src="../assets/img/h3-img-3.jpg" alt="">
        </div>
        <div class="col">
            <img src="../assets/img/h3-img-4.jpg" alt="">
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



</style>