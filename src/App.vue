<template>
  <div class="dimension" >
    <TheNav></TheNav>
    <div class="tb-bg-main"><TheMain></TheMain></div>
    <div class="tb-bg-banner"><TheBanner></TheBanner></div>
    <div class="tb-bg-footer"><TheFooter></TheFooter></div>
    <div class="tb-bg-navfooter"><TheNavFooter></TheNavFooter></div>
  </div>
  

</template>

<script>
import TheNav from './TheNav.vue';
import TheMain from './TheMain.vue';
import TheBanner from './TheBanner.vue';
import TheFooter from './TheFooter.vue';
import TheNavFooter from './TheNavFooter.vue';

export default {
  components: { TheNav, TheMain, TheBanner, TheFooter, TheNavFooter}
};
</script>

<style lang="scss">
  @use "./style/general.scss";
  @use "./style/partials/utilities.scss";
  @use "./style/partials/variables.scss";

  .dimension {
    width: 100vw;
  }

  .tb-bg-main {
        background-color: black;
    }

  .tb-bg-banner {
      background-color: #0082F0;
  }

  .tb-bg-footer {
    background-image: url(./footer-bg.jpg);
  }

  .tb-bg-navfooter {
    background-color: #333333;
  }
</style>
