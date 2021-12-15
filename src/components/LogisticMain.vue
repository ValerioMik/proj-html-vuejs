<template>
  <div id="containerMain">
    <!-- info -->
    <div class="sezione percentuali">
      <div class="centratura">
        <p class="piccoloP">about the network</p>
        <div id="sfondititoli"><h1>THE</h1></div>
        <div id="company"><h1>Company</h1></div>
        <p class="sottotioli">
          Lorem, ipsum dolor sit amet consect Lorem ipsum dolor sit amet
          consectetur, adipisicing elit.
        </p>
        <div class="containerPercentuali">
          <div class="circlePercentuale">0%</div>
          <div class="dx">
            <h2>Leaderschip</h2>
            <p>Lorem ipsum dolor  cupiditate necessitatibus aliquid quidem.</p>
          </div>
          <div class="circlePercentuale">0%</div>
          <div class="dx">
            <h2>Psychology</h2>
            <p>Lorem ipsum dolor  cupiditate necessitatibus aliquid quidem.</p>
          </div>
          <div class="circlePercentuale">1%</div>
          <div class="dx">
            <h2>Flexibility</h2>
            <p>Lorem ipsum dolor  cupiditate necessitatibus aliquid quidem.</p>
          </div>
        </div>
      </div>
    </div>
    <div class="sezione immagine"></div>
    <!-- news -->
    <!-- newsletter -->
    <!-- Invio messaggi -->
  </div>
</template>

<script>
export default {
  name: "LogisticMain",
  props: {},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.centratura {
  width: 60%;
  margin: 0 auto;
}
#containerMain {
  display: flex;
  flex-wrap: wrap;
  margin-top: 1299px;
}
.sezione {
  width: 50%;
  height: 1009px;
}
.percentuali {
  background-color: black;
  display: flex;
  flex-wrap: wrap;
}
.immagine {
  background-image: url("../../src/assets/about-5.jpg");
  background-position: -151px, 2px;
  background-size: cover;
}
.piccoloP {
  color: #88e2e3;
}
h1,
.sottotioli {
  color: white;
}
#sfondititoli {
  background-color: #0c2a2b;
  border-radius: 5px;
  width: 88px;
  text-align: center;
  display: inline-block;
}
#company {
  display: inline-block;
}
</style>
