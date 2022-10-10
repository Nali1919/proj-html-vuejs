<template>
    <div class="ac-container my-1">
        <div class="ac-row ">
            <div class="col img-1">
                <img src="../assets/img/h1-team-1a-700x700.jpg" alt="">

                <div class="hidden-menu">
                    <h5>Mark Lenders</h5>
                    <span>Cuoco</span>
                    <div class="flex-icon">
                        <span class="white"><i class="fa-brands fa-twitter"></i> </span>
                        <span class="white"> <i class="fa-brands fa-facebook-f"></i> </span>
                        <span class="white"> <i class="fa-brands fa-instagram"></i> </span>
                    </div>
                </div>

            </div>
            <div class="col img-2">
                <img src="../assets/img/h1-team-2a.jpg" alt="">

                <div class="hidden-menu">
                    <h5>Giulia Bianchi</h5>
                    <span>Cameriera</span>
                    <div class="flex-icon">
                        <span class="white"><i class="fa-brands fa-twitter"></i> </span>
                        <span class="white"> <i class="fa-brands fa-facebook-f"></i> </span>
                        <span class="white"> <i class="fa-brands fa-instagram"></i> </span>
                    </div>
                </div>
            </div>
            <div class="col img-3">
                <img src="../assets/img/h1-team-3a.jpg" alt="">

                <div class="hidden-menu">
                    <h5>Giada Borghi</h5>
                    <span>Caposala</span>
                    <div class="flex-icon">
                        <span class="white"><i class="fa-brands fa-twitter"></i> </span>
                        <span class="white"> <i class="fa-brands fa-facebook-f"></i> </span>
                        <span class="white"> <i class="fa-brands fa-instagram"></i> </span>
                    </div>
                </div>
            </div>
            <div class="col img-4">
                <img src="../assets/img/h1-team-4a.jpg" alt="">

                <div class="hidden-menu">
                    <h5>Bill Bloom</h5>
                    <span>Fattorino</span>
                    <div class="flex-icon">
                        <span class="white"><i class="fa-brands fa-twitter"></i> </span>
                        <span class="white"> <i class="fa-brands fa-facebook-f"></i> </span>
                        <span class="white"> <i class="fa-brands fa-instagram"></i> </span>
                    </div>
                </div>
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
.ac-container img {
    width: 100%;
}

.ac-row {
    display: flex;
}

.img-1,
.img-2,
.img-3,
.img-4 {
    position: relative;
    overflow-y: hidden;
}

.hidden-menu {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    width: 330px;
    height: 330px;
    background-color: orange;
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    margin: auto;
    opacity: 0;
}

.img-1:hover .hidden-menu {
    opacity: 1;
}

.img-2:hover .hidden-menu {
    opacity: 1;
}

.img-3:hover .hidden-menu {
    opacity: 1;
}

.img-4:hover .hidden-menu {
    opacity: 1;
}

.flex-icon {
    display: flex;
    column-gap: 5px;
    cursor: pointer;
}

.white {
    color: white;
}
</style>