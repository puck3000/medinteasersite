<template>
  <div class="embed-container">
    <iframe src="https://www.youtube.com/embed/-q3qkLKBdvE?autoplay=1&modestbranding=1&showinfo=0&rel=0" frameborder="0" allowfullscreen></iframe>
  </div>
</template>

<script>
export default {};
</script>

<style lang="stylus" scoped>
.embed-container {
  position: relative;
  padding-bottom: 56.25%;
  height: 0;
  overflow: hidden;
  max-width: 100%;
  margin-bottom: 1rem;

  @media screen and (min-width: 768px) {
    margin-bottom: 2rem;
  }
}

.embed-container iframe, .embed-container object, .embed-container embed {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}
</style>
