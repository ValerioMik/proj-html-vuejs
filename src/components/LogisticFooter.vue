<template>
  <div id="containerfooter">
    <div class="centratura">
      <!-- logo ed info -->
      <div class="orariLogo">
        <div id="logo">
          <h1 class="logoFattoaMano">NEXT</h1>
        </div>
        <h1 class="logoDue">GEN</h1>
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
            <i class="fas fa-map-marker-alt"></i>
            <span>Hello@example.com</span>
          </div>
          <div class="buttonbianco">
            <a href="#"><h4 class="colreazzurro">Get in touch</h4></a>
          </div>
        </section>
      </div>
      <!-- about -->
      <LogisticVocifooter
        v-for="(voce, i) in vociFooter"
        :key="i"
        :dettagli="voce"
      />
    </div>
  </div>
</template>

<script>
import LogisticVocifooter from "@/components/LogisticVocifooter.vue";

export default {
  name: "LogisticFooter",
  components: {
    LogisticVocifooter,
  },
  data() {
    return {
      vociFooter: [
        {
          title: "About",
          options: [
            "The Company",
            "Institutional",
            "Social & events",
            "Innovation",
            "Enviroment",
            "Technology",
          ],
        },
        {
          title: "Transport",
          options: [
            "Industrialized",
            "Chemicals",
            "Packaged Liquids",
            "Constrution",
            "Laminated Wood",
            "And others",
          ],
        },
        {
          title: "Company",
          options: [
            "Resposibility",
            "Tearms of use",
            "About Cookies",
            "Privacy Policy",
            "Accessibility",
            "Informations",
          ],
        },
      ],
    };
  },
  props: {},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
#containerfooter {
  background-image: url("../../src/assets/bg-10.jpg");
  background-repeat: no-repeat;
  filter: brightness(0.9) contrast(1);
  height: 500px;
  width: 100%;
  bottom: 3px;
  background-position: -113px -359px;
}
.centratura {
  width: 70%;
  margin: 0 auto;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
  padding: 72px;
}

#logo {
  background-color: #75a7a8;
  border-radius: 20px 0px 0px 20px;
  opacity: 0.7;
  display: inline-block;
  margin-bottom: 30px;
}
.logoDue {
  color: white;
  display: inline-block;
}
.logoFattoaMano {
  color: #8cdadc;
  text-align: center;
}
.about {
  width: 22%;
  border-radius: 20px 20px 20px 20px;
  background-color: rgba(255, 255, 255, 0.1);
}
a{
  text-decoration: none;
  }

span,
i,
h2 {
  color: white;
  text-align: center;
}
.info {
  margin: 27px 0px;
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
h4{
  color: white;
}
</style>
