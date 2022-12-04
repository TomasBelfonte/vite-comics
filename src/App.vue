<template>
  <TheNav></TheNav>
  <h1>testo di prova</h1>
  <h1>sono veramente felice quando le cose funzionano</h1>

</template>

<script>
import TheNav from './TheNav.vue';

export default {
  components: { TheNav }
};
</script>

<style lang="scss">
  @use "./style/general.scss";
  @use "./style/partials/utilities.scss";
  @use "./style/partials/variables.scss";

  body {    
    width: 1200px;
    margin: 0 auto;
    
}

</style>
