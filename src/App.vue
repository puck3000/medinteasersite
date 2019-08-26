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
  },
  metaInfo: {
    meta: [
      // OpenGraph data (Most widely used)
      { property: "og:title", content: "Medin Biel Bienne | Teasersite" },
      { property: "og:site_name", content: "Medin Biel Bienne | Teasersite" },
      // The list of types is available here: http://ogp.me/#types
      { property: "og:type", content: "website" },
      // Should the the same as your canonical link, see below.
      { property: "og:url", content: "https://medinteasersite.netlify.com/" },
      { property: "og:image", content: "@/assets/img/Poster.jpg" },
      // Often the same as your meta description, but not always.
      {
        property: "og:description",
        content: "Teaserseite für Medin Biel/Bienne | ab Oktober 2019"
      },

      // Twitter card
      {
        name: "twitter:card",
        content: "Teaserseite für Medin Biel/Bienne | ab Oktober 2019"
      },
      { name: "twitter:site", content: "https://medinteasersite.netlify.com/" },
      { name: "twitter:title", content: "Medin Biel Bienne | Teasersite" },
      {
        name: "twitter:description",
        content: "Teaserseite für Medin Biel/Bienne | ab Oktober 2019"
      },
      // Your twitter handle, if you have one.
      { name: "twitter:creator", content: "@medinbielbienne" },
      { name: "twitter:image:src", content: "@/assets/img/Poster.jpg" },

      // Google / Schema.org markup:
      { itemprop: "name", content: "Medin Biel Bienne | Teasersite" },
      {
        itemprop: "description",
        content: "Teaserseite für Medin Biel/Bienne | ab Oktober 2019"
      },
      { itemprop: "image", content: "@/assets/img/Poster.jpg" }
    ]
  }
};
</script>

<style lang="stylus">
@import 'assets/styles/fonts.styl';

html, body, #app {
  margin: 0;
  padding: 0;
}

.video {
  max-width: 1200px;
  margin: auto;
}

.video {
  width: 100%;
}
</style>

