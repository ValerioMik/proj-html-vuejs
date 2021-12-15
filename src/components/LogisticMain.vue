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
    <div class="newsletter">
      <div class="centraturaloghi centdue">
        <div class="know">
          <div>
            <p class="piccoloP">newsletter</p>
          </div>
          <div id="sfondititoli2">
            <h1 class="h1nero">Know</h1>
          </div>
          <div id="company">
            <h1 class="colreazzurro">first</h1>
          </div>
          <div class="contenitore">
            <div class="paragrafo">
              <p class="sottotioli2">Lorem, ipsum dolor sit amet consect</p>
            </div>
          </div>
        </div>
        <div class="input">
          <div><input type="text" placeholder="Name" /></div>
          <div><input type="text" placeholder="Email" /></div>
          <div class="button">
            <a href="#"><h4>Subscribe</h4></a>
          </div>
        </div>
      </div>
    </div>
    <!-- Invio messaggi -->
    <div class="messaggi">
      <div class="centraturamessaggi">
        <div class="sx">
          <div><div>
            <p class="piccoloP">newsletter</p>
          </div>
          <div id="company">
            <h1 class="h1nero">Get In</h1>
          </div>
          <div id="sfondititoli2">
            <h1 class="colreazzurro">Touch</h1>
          </div>
          <div class="contenitore">
            <div class="paragrafo">
              <p class="sottotioli2">Lorem, ipsum dolor sit amet consect</p>
            </div>
            <div class="scrivimessaggio">
              </div><input class="mess" type="text" placeholder="Name"> <input class="mess" type="text" placeholder="Phone"></div>
              <div><input class="mess" type="text" placeholder="Email"> <input class="mess" type="text" placeholder="More info"></div>
            </div>
            <div><input class="messdue" type="text" placeholder="Message"></div>
            <div class="button">
            <a href="#"><h4>Send</h4></a>
          </div>
          </div>
        <div class="dx">
          <div class="orariLogo">
            <p class="sottotioli2">
              Lorem ipsum dolor, sit amet consectetur adipisicing elit. 
            </p>
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
                <a href="#"><h4 class="colreazzurro">View Map</h4></a>
              </div>
            </section>
          </div>
        </div>
      </div>
    </div>
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
.messaggi {
  background-color: #e5ebe5;
  width: 100%;
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
  justify-content: space-between;
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
  width: 111px;
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
.buttonbianco {
  border-radius: 5px;
  width: 100px;
  height: 50px;
  display: flex;
  align-items: center;
  justify-content: center;
  border: solid 3px #048383;
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

.newsletter {
  background-image: url("../../src/assets/bg-1.jpg");
  background-position: left -350px bottom -269px;
  height: 504px;
  width: 100%;
  display: flex;
}
input {
  width: 500px;
  height: 50px;
  margin-top: 15px;
  margin-bottom: 10px;
  filter: opacity(0.3);
  padding-left: 15px;
}
.centdue {
  width: 60%;
}
.centraturamessaggi{
  width: 70%;
  margin: 75px auto;
  display: flex;
  justify-content: space-between;
}

.scrivimessaggio{
  display: flex;
}
.mess{
width: 238px;
}
.messdue{
  height: 150px;
}
.info {
  margin: 60px 0px;
}
</style>
