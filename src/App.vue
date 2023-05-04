<script>
import HeaderDc from './components/HeaderDc.vue';
import darkContainer from './components/darkContainer.vue';
import lightBlueContainer from './components/lightBlueContainer.vue'

export default {
    name: "App",
    components: {
      HeaderDc,
      darkContainer,
      lightBlueContainer
    }
  }
</script>

<template>
  <HeaderDc/>
  <darkContainer/>
  <lightBlueContainer/>
</template>

<style>

</style>
