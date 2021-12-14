<template>
  <!-- jumbotron -->
  <li id="vociMenu">
    <a href="#">{{ dettagli.text }}</a>
  </li>
</template>

<script>
export default {
  name: "LogisticJumbotron",
  props: {
    dettagli: Object,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
i {
  font-size: 15px;
  color: white;
  margin: 4px;
}
a {
  color: white;
  text-decoration: none;
  margin-right: 30px;
}
li {
  list-style-type: none;
}
</style>
