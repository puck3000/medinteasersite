<template>
  <video
    controls
    autoplay
    loop
    plays-inline
    playsinline
    poster="SocialImgs/MEDIN-BielBiennne_FB_Image_1200x630.jpg"
  >
    <source src="video/medinTeaser.mp4" type="video/mp4" />
    <source src="video/medinTeaser.webm" type="video/webm" />
    <p>
      Your browser doesn't support HTML5 video. Here is a
      <a
        href="https://www.youtube.com/embed/-q3qkLKBdvE?autoplay=1&modestbranding=1&showinfo=0&rel=0"
      >link to the video</a> instead.
    </p>
  </video>
</template>

<script>
export default {};
</script>

<style lang="stylus" scoped>
video {
  width: 100%;
  margin-bottom: 1rem;

  @media screen and (min-width: 1200px) {
    margin-bottom: 2rem;
  }
}
</style>


