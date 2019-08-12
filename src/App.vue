<template>
  <div id="app">
    <Head />
    <main>
      <Youtube />
      <Content />
    </main>
  </div>
</template>

<script>
import Head from "./components/Head.vue";
import Youtube from "./components/Youtube.vue";
import Content from "./components/Content.vue";
export default {
  components: {
    Head,
    Youtube,
    Content
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

