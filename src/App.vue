<template>
  <div>
    <TheNav></TheNav>
    <TheSubNav></TheSubNav>
    <TheMain></TheMain>
    <TheBanner></TheBanner>
    <TheFooter></TheFooter>
    <TheNavFooter></TheNavFooter>
  </div>
  

</template>

<script>
import TheNav from './TheNav.vue';
import TheMain from './TheMain.vue';
import TheBanner from './TheBanner.vue';
import TheFooter from './TheFooter.vue';
import TheNavFooter from './TheNavFooter.vue';
import TheSubNav from './TheSubNav.vue'

export default {
  components: { TheNav, TheMain, TheBanner, TheFooter, TheNavFooter, TheSubNav}
};
</script>

<style lang="scss">
  @use "./style/general.scss";
  @use "./style/partials/utilities.scss";
  @use "./style/partials/variables.scss";

</style>
