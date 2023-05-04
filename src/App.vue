<script>
import HeaderDc from './components/HeaderDc.vue';
import darkContainer from './components/darkContainer.vue';
import lightBlueContainer from './components/lightBlueContainer.vue';
import darkListContainer from './components/darkListContainer.vue';
import darkFooter from './components/darkFooter.vue';

export default {
    name: "App",
    components: {
      HeaderDc,
      darkContainer,
      lightBlueContainer,
      darkListContainer,
      darkFooter
    }
  }
</script>

<template>
  <HeaderDc/>
  <darkContainer/>
  <lightBlueContainer/>
  <darkListContainer/>
  <darkFooter/>
</template>

<style>

</style>
