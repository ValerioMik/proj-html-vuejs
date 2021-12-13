<template>
  <div id="container">
    <div class="centratura">
      <!-- barra info orari numero ecc. -->
      <div id="barrainfo">
        <section class="orari">
          <i class="far fa-clock"></i>
          <span>Open Hours: Mon - sat - 9:00 - 18:00</span>
        </section>
        <section class="numeri">
          <div class="info">
            <i class="fas fa-phone-alt"></i>
            <span>+1 (305)1234-5678</span>
          </div>
          <div class="info">
            <i class="fas fa-envelope"></i>
            <span>Hello@example.com</span>
          </div>
          <div class="info">
            <div><i class="fab fa-facebook-f"></i></div>
            <div><i class="fab fa-twitter"></i></div>
            <div><i class="fab fa-linkedin-in"></i></div>
          </div>
        </section>
      </div>
    </div>
    <!-- jumbotron -->
    <div id="jumbotron"></div>
        <div id="logo">
        </div>
        <div id="vociMenu">
        <ul>
            <li>
               <a href="">HOME</a>
            </li>
        </ul>
       
        </div>
    </div>
</template>

<script>
export default {
  name: "LogisticHeader",
  props: {},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.centratura {
  width: 80%;
  margin: 0 auto;
}

#barrainfo {
  display: flex;
  justify-content: space-around;
}
#container {
  height: 50px;
  background-color: rgb(33, 51, 62);
  align-items: center;
}
.far {
  color: white;
}
.fab {
  margin-right: 20px;
}
span {
  color: white;
  margin-left: 10px;
}
.numeri {
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.info {
  margin: 0 5px;
  display: flex;
  justify-content: space-around;
}
span,
i {
  font-size: 15px;
  color: white;
  margin: 4px;
}
#jumbotron {
    position: relative;
  margin-top: 13px;
  background-image: url("../../src/assets/jumbo.jpg");
  background-repeat: no-repeat;
  filter: brightness(0.6) contrast(1);
  height: 1130px;
  width: 100%;
  background-position: -133px -187px;
}
#vociMenu{
    position: absolute;
    top: 50px;
    right: 724px;
}

</style>
