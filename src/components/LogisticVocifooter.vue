<template>
  <div class="about">
        <h2>{{dettagli.title}}</h2>
        <ul>
          <li v-for="voce, i in dettagli.options" :key="i"><i class="fas fa-chevron-right"></i>{{voce}}</li>
        </ul>
      </div>
</template>

<script>
export default {
  name: "LogisticVocifooter",
  props: {
    dettagli: Object,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
span,
i,
h2,li {
  color: white;
  text-align: center;
}
.info {
  margin: 27px 0px;
}
li {
  list-style-type: none;
}
.fas{
    margin-right: 20px;
    margin-top: 6px;
}
</style>
