<template>
  <div id="app">
    <LogisticHeader/>
    <LogisticMain/>
    <LogisticFooter/>
  </div>
</template>

<script>
import LogisticHeader from './components/LogisticHeader.vue'
import LogisticMain from './components/LogisticMain.vue'
import LogisticFooter from './components/LogisticFooter.vue'

export default {
  name: 'App',
  components: {
    LogisticHeader,
    LogisticMain,
    LogisticFooter
  },
  data(){
    return {
      vociMenu:[
        {
          "text":"HOME"
       },
       {
          "text":"SERVICES"
       },
       {
          "text":"SKILLS"
       },
       {
          "text":"PARTNERS"
       },
       {
          "text":"BLOG"
       },
       {
          "text":"GET IN TOUCH"
       },
      ]
    }
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
 
}
</style>
