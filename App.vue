<template>
  <navbar></navbar>
  <variables></variables>
  <loop></loop>
  <footerComp></footerComp>
</template>



<script>
import navbar from './components/navbar.vue';
import footerComp from './components/footer.vue';
import variables from './components/variables.vue';
import loop from "./components/loop.vue"

export default {
  components: {
    navbar,
    footerComp,
    variables,
    loop,
  },
}
</script>





<style></style>