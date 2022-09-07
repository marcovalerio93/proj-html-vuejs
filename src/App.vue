<template>
  <div id="app">
    <HeaderJambo/>
    <myClass/>
    <myContent/>
    <myResults/>
    <myPerformance/>
    <myTrainers/>
    <myFooter/>

  </div>
</template>

<script>

import HeaderJambo from './components/HeaderJambo.vue';
import myClass from './components/myClass.vue';
import myContent from './components/myContent.vue';
import myResults from './components/myResults.vue';
import myPerformance from './components/myPerformance.vue';
import myTrainers from './components/myTrainers.vue';
import myFooter from './components/myFooter.vue';



export default {
  name: 'App',
  components: {
    HeaderJambo,
    myClass,
    myContent,
    myResults,
    myPerformance,
    myTrainers,
    myFooter
  }
}
</script>

<style lang="scss">

  @import '~@fortawesome/fontawesome-free/css/all.css';

  @import './styles/generals.scss';

</style>
