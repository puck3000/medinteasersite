<template>
  <footer>
    <div class="innerFooter">
      <h2>MEDIN Biel/Bienne</h2>
      <p class="bmarg1">
        <a href="https://goo.gl/maps/nq5QtWm4yNP9wBJj7" target="_blank" rel="noopener">
          Bahnhofplatz 2c
          <br />2502 Biel/Bienne
        </a>
      </p>
      <p>
        <a href="tel:+410320000000">032 000 00 00</a>
      </p>
      <p>
        <a href="mailto:xy@xaasd.ch">E-Mail</a>
      </p>
      <p>
        <a href="https://medin-bielbienne.ch">medin-bielbienne.ch</a>
      </p>
    </div>
  </footer>
</template>

<script>
export default {};
</script>

<style lang="stylus" scoped>
footer {
  background-color: blue;
  color: #F5F5F5;
  padding: 2rem 0.5rem;
}

.innerFooter {
  max-width: 1200px;
  margin: auto;
}

.bmarg1 {
  margin-bottom: 1rem;
}

a {
  text-decoration: none;

  &:hover {
    text-decoration: underline;
    color: #F5F5F5;
  }
}
</style>

