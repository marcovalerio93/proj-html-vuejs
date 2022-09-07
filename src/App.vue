<template>
  <div id="app">
    <HeaderJambo/>
    <myClass/>
    <myResults/>
    <myPerformance/>
    <myTrainers/>
    <myFooter/>
  </div>
</template>

<script>

import HeaderJambo from './components/HeaderJambo.vue';
import myClass from './components/myClass.vue';
import myResults from './components/myResults.vue';
import myPerformance from './components/myPerformance.vue';
import myTrainers from './components/myTrainers.vue';
import myFooter from './components/myFooter.vue';



export default {
  name: 'App',
  components: {
    HeaderJambo,
    myClass,
    myResults,
    myPerformance,
    myTrainers,
    myFooter
  }
}
</script>

<style lang="scss">

  @import './styles/generals.scss';

</style>
