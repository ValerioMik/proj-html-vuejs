<template>
  <div id="containerfooter">
      <div class="centratura">
        <!-- logo ed info -->
      <div class="orariLogo">
        <div id="logo">
      <h1 class="logoFattoaMano">NEXT</h1>
    </div>
    <h1 class="logoDue">GEN</h1>
      </div>
      <!-- about -->
      <div class="about"></div>
      <!-- trasport -->
      <div class="trasporti"></div>
      <!-- support -->
      <div class="supporto"></div>

      </div>
  </div>
</template>

<script>
export default {
  name: 'LogisticFooter',
  props: {
   
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
#containerfooter{
  background-image: url("../../src/assets/bg-10.jpg");
  background-repeat: no-repeat;
  filter: brightness(0.6) contrast(1);
  height: 500px;
  width: 100%;
  margin-top: 881px;
  bottom: 3px;
  background-position: -113px -359px;
}
.centratura{
 width: 70%;
 margin: 0 auto;
}
</style>
