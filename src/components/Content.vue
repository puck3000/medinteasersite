<template>
  <div class="maincontent">
    <section class="de">
      <h2>Medin Biel,
        <br>ab Oktober 2019</h2>
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
      <h2>Medin Bienne,
        <br>
        des octobre 2019</h2>
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
  padding: 1rem;
  @media screen and (min-width: 1200px) {
    padding: 0;
  }

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

ul 
  position: relative;
  list-style: none;
  margin-left: 0;
  padding-left: 2rem;
  li 
    &::before 
      content: "→";
      position: absolute;
      left: 0;
      transition: left .3s ease-in-out
    &:hover 
      color: blue
      &::before 
        left: .25rem
    a 
      text-decoration: none

p 
  margin-bottom: 1rem

</style>