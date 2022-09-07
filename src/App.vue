<template>
  <div id="app">
    <HeaderJambo/>
    <MyClass/>
    <MyContent/>
    <MyResults/>
    <MyPerformance/>
    <MyTrainers/>
    <MyFooter/>

  </div>
</template>

<script>

import HeaderJambo from './components/HeaderJambo.vue';
import MyClass from './components/MyClass.vue';
import MyContent from './components/MyContent.vue';
import MyResults from './components/MyResults.vue';
import MyPerformance from './components/MyPerformance.vue';
import MyTrainers from './components/MyTrainers.vue';
import MyFooter from './components/MyFooter.vue';



export default {
  name: 'App',
  components: {
    HeaderJambo,
    MyClass,
    MyContent,
    MyResults,
    MyPerformance,
    MyTrainers,
    MyFooter
  }
}
</script>

<style lang="scss">

  @import '~@fortawesome/fontawesome-free/css/all.css';

  @import './styles/generals.scss';

</style>
