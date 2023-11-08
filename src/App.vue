<template>
  <div>
  <h1>lol</h1>
  
  <mycomponent class="title"></mycomponent>
  <component3></component3>
  <AppHero></AppHero>
  
  </div>
</template>

<script>
 import mycomponent from './components/apptitle.vue'; 
 import component3 from './components/component3.vue';
 import AppHero from './components/AppHero.vue';

export default {
 
  setup () {
    

    return {}
  },
  components: {
    mycomponent, 
    component3,
    AppHero,
  },
}
</script>

<style lang="css" scoped>
 .title{
  text-align: center;
  font-size: 3em;
 }
</style>
