<template>
  <div class="dimension" >
    <TheNav></TheNav>
    <div class="tb-bg-main"><TheMain></TheMain></div>
    <div class="tb-bg-banner"><TheBanner></TheBanner></div>
    <h1>testo di prova</h1>
    <h1>sono veramente felice quando le cose funzionano</h1>
  </div>
  

</template>

<script>
import TheNav from './TheNav.vue';
import TheMain from './TheMain.vue';
import TheBanner from './TheBanner.vue';

export default {
  components: { TheNav, TheMain, TheBanner}
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
</style>
