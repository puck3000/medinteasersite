<template>
  <div id="app">
    <Head />
    <main>
      <Youtube />
      <Content />
    </main>
    <Foot />
  </div>
</template>

<script>
import Head from "./components/Head.vue";
import Youtube from "./components/Youtube.vue";
import Content from "./components/Content.vue";
import Foot from "./components/Foot.vue";
export default {
  components: {
    Head,
    Youtube,
    Content,
    Foot
  }
};
</script>

<style lang="stylus">
@import 'assets/styles/fonts.styl';

html, body, #app {
  margin: 0;
  padding: 0;
}

main {
  max-width: 1200px;
  margin: auto;
}
</style>

