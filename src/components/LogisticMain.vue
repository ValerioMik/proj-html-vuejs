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
            <p>Lorem ipsum dolor cupiditate necessitatibus aliquid quidem.</p>
          </div>
          <div class="circlePercentuale">0%</div>
          <div class="dx">
            <h2>Psychology</h2>
            <p>Lorem ipsum dolor cupiditate necessitatibus aliquid quidem.</p>
          </div>
          <div class="circlePercentuale">1%</div>
          <div class="dx">
            <h2>Flexibility</h2>
            <p>Lorem ipsum dolor cupiditate necessitatibus aliquid quidem.</p>
          </div>
        </div>
      </div>
    </div>
    <div class="sezione immagine"></div>
    <!-- loghi -->
    <div class="loghiAziende">
      <div class="centraturaloghi">
        <div class="cardlogo"><img src="..\assets\logo-5.png" alt="" /></div>
        <div class="cardlogo"><img src="..\assets\logo-1.png" alt="" /></div>
        <div class="cardlogo"><img src="..\assets\logo-2.png" alt="" /></div>
        <div class="cardlogo"><img src="..\assets\logo-3.png" alt="" /></div>
        <div class="cardlogo"><img src="..\assets\logo-4.png" alt="" /></div>
        <div class="cardlogo"><img src="..\assets\logo-5.png" alt="" /></div>
      </div>
    </div>
    <!-- news -->
    <div class="news">
      <div class="centraturaH1">
        <p class="piccoloP">about the network</p>
        <div id="company"><h1 class="h1nero">Latest</h1></div>
        <div id="sfondititoli2"><h1 class="colreazzurro">News</h1></div>
        <div class="contenitore_p_Button">
          <div class="paragrafo">
            <p class="sottotioli2">Lorem, ipsum dolor sit amet consect</p>
          </div>
          <div class="button">
            <a href="#"><h4>See ALL</h4></a>
          </div>
        </div>
      </div>
      <div class="centraturaloghi">
        <div class="imagininews uno">
          <p>increasing creativity is possible for everyone</p>
        </div>
        <div class="imagininews due">
          <p>Because market research is part of the business plan</p>
        </div>
        <div class="imagininews tre">
          <p>Working from home is now a trend</p>
        </div>
      </div>
    </div>
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
  margin: 116px 238px;
}
.containerPercentuali {
  width: 420px;
  display: flex;
  flex-wrap: wrap;
}
#containerMain {
  display: flex;
  flex-wrap: wrap;
  margin-top: 1400px;
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
h2,
p,
h4,
.sottotioli {
  color: white;
}
.sottotioli2 {
  color: black;
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
.circlePercentuale {
  border-radius: 50%;
  width: 36px;
  height: 36px;
  padding: 10px;
  border: 5px solid rgb(37, 37, 37);
  color: rgb(255, 255, 255);
  text-align: center;
  font: 20px Arial, sans-serif;
  display: inline-block;
  margin-right: 37px;
}
.dx {
  display: flex;
  flex-wrap: wrap;
  flex-direction: column;
}
.loghiAziende {
  background-color: #e5ebe5;
  height: 200px;
  width: 100%;
}
.centraturaloghi {
  width: 70%;
  margin: 75px auto;
  display: flex;
  flex-wrap: wrap;
  align-content: space-around;
}
.cardlogo {
  width: 16%;
  margin-left: 5px;
}
img {
  width: 70px;
  filter: invert(0.5);
}
.centraturaH1 {
  width: 70%;
  margin: 78px auto;
}
.h1nero {
  color: black;
}

.colreazzurro {
  color: #048383;
}
#sfondititoli2 {
  background-color: #bfdcdd;
  border-radius: 5px;
  width: 88px;
  text-align: center;
  display: inline-block;
}
.news {
  width: 100%;
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
a {
  text-decoration: none;
}
.contenitore_p_Button {
  display: flex;
  justify-content: space-between;
}
.uno {
  background-image: url("../../src/assets/news-1.jpg");
}
.due {
  background-image: url("../../src/assets/news-2.jpg");
}

.tre {
  background-image: url("../../src/assets/news-3.jpg");
}

.imagininews {
  background-repeat: round;
  margin-right: 50px;
  height: 250px;
  width: 26%;
  border-radius: 15px;
  display: flex;
  align-items: flex-end;
  text-align: center;
}
</style>
