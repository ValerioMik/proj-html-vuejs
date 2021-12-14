<template>
  <div class="about">
        <h2>{{dettagli.title}}</h2>
        <ul>
          <li v-for="voce, i in dettagli.options" :key="i">{{voce}}</li>
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
</style>
