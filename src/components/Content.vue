<template>
  <div class="maincontent">
    <section class="de">
      <h2>Medin Biel, ab Oktober 2019</h2>
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Nesciunt voluptas
        nostrum nisi necessitatibus, itaque, impedit dolor totam nam velit atque
        dignissimos consequuntur sunt odit voluptate blanditiis magni at labore
        sequi aspernatur mollitia beatae vero, inventore placeat corporis. Minima,
        fugiat corporis!
      </p>
      <p>
        Mehr informationen
        <a href="tel:+410320000000">032 000 00 00</a> oder
        <a href="mailto:xy@xaasd.ch">E-Mail</a>
        <ul>
          <li>
            <a href="#">
              Infos für Medien
            </a>
          </li>
          <li>
            <a href="#">
              Infos für ÄrztInnen
            </a>
          </li>
          <li>             
            <a href="#">
              Infos für Patienten
            </a>
          </li>
        </ul>
      </p>
    </section>
    <section class="fr">
      <h2>Medin Bienne, des octobre 2019</h2>
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Nesciunt voluptas
        nostrum nisi necessitatibus, itaque, impedit dolor totam nam velit atque
        dignissimos consequuntur sunt odit voluptate blanditiis magni at labore
        sequi aspernatur mollitia beatae vero, inventore placeat corporis. Minima,
        fugiat corporis!
      </p>
      <p>Mehr informationen
        <a href="tel:+410320000000">032 000 00 00</a> oder
        <a href="mailto:xy@xaasd.ch">E-Mail</a>
        <ul>
          <li>
            <a href="#">
              Infos für Medien
            </a>
          </li>
          <li>
            <a href="#">
              Infos für ÄrztInnen
            </a>
          </li>
          <li>             
            <a href="#">
              Infos für Patienten
            </a>
          </li>
        </ul></p>
    </section>
  </div>
</template>

<script>
export default {};
</script>

<style lang="stylus" scoped>
.maincontent 
  padding: 0.5rem;

section {
  margin-bottom: 2rem;

  @media screen and (min-width: 768px) {
    width: 45%;
    display: inline-block;

    &.de {
      margin-right: 5%;
      float: left;
    }
  }
}

ul li 
  // list-style-image: url('~/assets/')
  &:hover 
    color: blue
  a 
    text-decoration: none

p 
  margin-bottom: 1rem

</style>



