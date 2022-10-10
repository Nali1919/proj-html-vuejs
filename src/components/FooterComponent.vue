<template>
  <div class="container-ac">
    <div class="row">
      <div class="img-left col-6">
        <div class="footer-alto">
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
                <span class="white"> <i class="fa-brands fa-instagram"></i> </span>
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
        <div class="footer-basso">
          <div>
            <div> <span class="orange">Created with<i class="fa-regular fa-heart"></i> .by</span> <span
                class="green">Qqode interactive</span>
            </div>
          </div>
          <div>
            <img class="footer-img" src="../assets/img/h1-img-7n.png" alt="">
          </div>

        </div>
      </div>
      <div class="img-right col-6">
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
.container-ac {
  margin-top: 10px;

}



.img-left {
  background-image: url(../assets/img/background-img-header.png);
  padding: 20px;
}

.img-right {
  background-image: url(../assets/img/footer-img-1.jpg);
  background-size: cover;
  background-position: center;

}

.flex-column {
  display: flex;
  flex-direction: column;
  margin: 5px;
  row-gap: 10px;

}

h6 {
  color: orange;
  font-size: 10px;
}

span {
  color: gray;
  font-size: 10px;
}

h4 {
  color: white;
  font-size: 18px;
}

.text {
  width: 160px;
}

.column {
  display: flex;
  flex-direction: column;
  margin-bottom: 10px;
}

.red {
  color: red
}

.orange {
  color: orange;
}

.icon {
  display: flex;
  column-gap: 10px;
}

.white {
  color: white;
}

.footer-alto {
  display: flex;
  padding: 40px;
  column-gap: 15px;
}

.footer-basso {
  display: flex;
  justify-content: space-between;
  align-items: flex-end;
  color: white;
  margin: 40px;
}

.footer-img {
  width: 80px;
}

.orange {
  color: orange;
}

.green {
  color: green;
}
</style>