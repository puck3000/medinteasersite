<template>
  <header>
    <div class="innerHeader">
      <div class="logos">
        <h1>
          <Logo :color="color" />
        </h1>
        <h2>Biel/Bienne</h2>
      </div>
    </div>
  </header>
</template>

<script>
import Logo from "./Logo.vue";
export default {
  components: {
    Logo
  },
  data() {
    return {
      color: "#F5F5F5"
    };
  }
};
</script>

<style lang="stylus" scoped>
header {
  background-color: blue;
  height: 4rem;
  margin-bottom: 1rem;
}

.innerHeader {
  max-width: 1200px;
  margin: auto;
  height: 4rem;
  display: flex;
  align-items: center;
}

.logos {
  width: 100%;
}

h1, h2 {
  margin: 0;
  display: inline;
}

h2 {
  font-family: 'SuisseIntl', 'Helvetica Neue', Helvetica, Arial, sans-serif;
  font-size: 10px;
  font-size: 0.85rem;
  line-height: 1.2;
  text-transform: none;
  color: #F5F5F5;
  font-weight: 400;
  padding-left: 1rem;
}
</style>

