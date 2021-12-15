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
    <div id="jumbotron">
      <div class="overlay"></div>
      <div id="logo">
        <h1 class="logoFattoaMano">NEXT</h1>
      </div>
      <h1 class="logoDue">GEN</h1>
      <ul class="vocimenuCentratura">
        <LogisticJumbotron
          v-for="(voci, i) in vociMenu"
          :key="i"
          :dettagli="voci"
        />
      </ul>
      <div class="overflow2"></div>
      <div class="future">
        <h1 class="titolo">logistics that goes Future.</h1>
        <p class="bianco">
          for 20 years working with the most innovation in the field of
          traspport
        </p>
        <div class="duebutt">
          <div class="button">
            <a href="#"><h4>Send</h4></a>
          </div>
          <div class="buttonbianco">
            <a href="#"><h4 class="colreazzurro">View Map</h4></a>
          </div>
        </div>
      </div>
    </div>
    <div class="colore">
      <div class="logisticservice">
        <div class="service">
          <p>OURS BISNES AREA</p>
          <h1>LOGISTIC SERVICES</h1>
          <p>
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Similique
            eius corrupti officia suscipit ducimus quidem dolorem vitae dolor
            est dignissimos nulla recusandae reiciendis ullam, aliquam eligendi,
            tempore quasi dolorum ipsam?
          </p>
        </div>
        <div class="card">
          <img src="../assets/gallery-3.jpg" alt="foto prova" />
          <h2>Tecnology</h2>
          <p>
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sit
            accusamus ipsa ab in omnis aliquid
          </p>
        </div>
        <div class="card">
          <img src="../assets/gallery-5.jpg" alt="foto prova" />
          <h2>trasport</h2>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Asperiores
            ipsa iste vel deserunt dolorum inventore
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import LogisticJumbotron from "@/components/LogisticJumbotron.vue";

export default {
  name: "LogisticHeader",
  components: {
    LogisticJumbotron,
  },
  data() {
    return {
      vociMenu: [
        {
          text: "HOME",
        },
        {
          text: "SERVICES",
        },
        {
          text: "SKILLS",
        },
        {
          text: "PARTNERS",
        },
        {
          text: "BLOG",
        },
        {
          text: "GET IN TOUCH",
        },
      ],
    };
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.centratura {
  width: 80%;
  margin: 0 auto;
}
.vocimenuCentratura {
  position: absolute;
  top: 55px;
  right: 166px;
  display: flex;
  align-items: flex-end;
}

#barrainfo {
  display: flex;
  justify-content: space-around;
  align-items: flex-end;
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
  margin-top: 5px;
  background-image: url("../../src/assets/jumbo.jpg");
  background-position: -133px -187px;
}
.overlay {
  height: 894px;
  width: 100%;
  background-color: rgba(0, 0, 0, 0.6);
}

a {
  color: white;
  text-decoration: none;
}
li {
  list-style-type: none;
}
#logo {
  position: absolute;
  height: 53px;
  width: 112px;
  top: 58px;
  left: 279px;
  background-color: #83a7a8;
  border-radius: 20px 0px 0px 20px;
  opacity: 0.3;
}
.logoFattoaMano {
  color: #8cdadc;
  text-align: center;
}
.logoDue {
  position: absolute;
  color: white;
  top: 50px;
  left: 393px;
}
.logisticservice {
  width: 70%;
  margin: 0 auto;
  height: 50338px0px;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
  padding: 65px;
}
.colore {
  background-color: #edf4ec;
}
.card {
  width: 25%;
  background-color: white;
  padding: 30px;
  border-radius: 20px;
}
.service {
  width: 25%;
}
img {
  width: 100%;
}
.future {
  position: absolute;
  top: 140px;
  right: 325px;
  width: 263px;
}
.overflow2 {
  background-color: #048383;
  position: absolute;
  top: 190px;
  right: 383px;
  width: 203px;
  height: 25px;
}
.titolo {
  font-size: 50px;
  color: white;
}
.bianco {
  color: white;
}
.buttonbianco {
  border-radius: 5px;
  width: 100px;
  height: 50px;
  display: flex;
  align-items: center;
  justify-content: center;
  border: solid 3px #048383;
}
.button {
  background-color: #048383;
  width: 100px;
  height: 50px;
  display: flex;
  align-items: center;
  justify-content: center;
  border-radius: 10px;
}
.duebutt {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
}
</style>
