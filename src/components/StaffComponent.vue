<template>
 <div class="ac-container my-1">
    <div class="ac-row ">
        <div class="col">
            <img  src="../assets/img/h1-team-1a-700x700.jpg" alt="">
        </div>
        <div class="col">
            <img  src="../assets/img/h1-team-2a.jpg" alt="">
        </div>
        <div class="col">
            <img  src="../assets/img/h1-team-3a.jpg" alt="">
        </div>
        <div class="col">
            <img src="../assets/img/h1-team-4a.jpg" alt="">
        </div>

    </div>

  </div>
 
</template>

<script>
export default {
name: 'StaffComponent'

}
</script>

<style lang="scss" scoped>
  .ac-container img{
    width: 100%;
}
.ac-row{
    display: flex;
}  

</style>