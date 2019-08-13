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
      <p class="last">
        <a href="https://medin-bielbienne.ch">medin-bielbienne.ch</a>
      </p>
      <a id="hellalink" href="https://www.hellastudio.ch/" target="_blank" rel="noopener">
        <Hellasmile :color="color" />
      </a>
    </div>
  </footer>
</template>

<script>
import Hellasmile from "./Hellasmile.vue";
export default {
  components: {
    Hellasmile
  },
  data() {
    return {
      color: "#F5F5F5"
    };
  }
};
</script>

<style lang="stylus" scoped>
footer {
  background-color: blue;
  color: #F5F5F5;
  padding: 2rem 1rem;
}

.innerFooter {
  max-width: 1200px;
  position: relative;
  margin: auto;

  p.last {
    display: inline-block;
  }
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

#hellalink {
  position: absolute;
  right: 1rem;
  display: inline-block;
}
</style>

