<template>
  <div>
  <h1>lol</h1>
  
  <mycomponent></mycomponent>
  <component3></component3>
  
  </div>
</template>

<script>
 import mycomponent from './components/mycomponent.vue'; 
 import component3 from './components/component3.vue';

export default {
 
  setup () {
    

    return {}
  },
  components: {
    mycomponent, 
    component3,
  },
}
</script>

<style lang="css" scoped>

</style>
