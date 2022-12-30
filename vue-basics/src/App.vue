<template>
  <NavBarVue></NavBarVue>
  <FooterVue></FooterVue>
  <Iteration2Vue></Iteration2Vue>
  <Iteration3Vue></Iteration3Vue>
  <Iteration4Vue></Iteration4Vue>
 
</template>

<script>
import NavBarVue from './components/NavBar.vue';
import FooterVue from './components/Footer.vue';
import Iteration2Vue from './components/Iteration2.vue';
import Iteration3Vue from './components/Iteration3.vue';
import Iteration4Vue from './components/Iteration4.vue';

export default {
  components: {
    NavBarVue,
    FooterVue,
    Iteration2Vue,
    Iteration3Vue,
    Iteration4Vue
  },
 
}

</script>

<style>

</style>