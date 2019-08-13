<template>
  <div id="app">
    <Head />
    <main>
      <div class="video">
        <Video />
      </div>
      <Content />
    </main>
    <Foot />
  </div>
</template>

<script>
import Head from "./components/Head.vue";
import Video from "./components/Video.vue";
import Content from "./components/Content.vue";
import Foot from "./components/Foot.vue";
export default {
  components: {
    Head,
    Video,
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

.video {
  width: 100%;
}
</style>

