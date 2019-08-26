<template>
  <div class="maincontent">
    <section class="de">
      <h2>Medin Biel,
        <br>ab Oktober 2019</h2>
      <p>
        Die Nähe eines Hausarztes, die Spezialkenntnis einer Fachärztin und die
        Infrastruktur eines Spitals – alles auf einem Stockwerk direkt beim
        Bahnhof.
        <br>
        <br>
        Jetzt einen dringenden Termin bei einem Hausarzt? 
        <br>
        Localmed Biel <a href="tel:+41323295500">032 329 55 00</a>  
        <br>
        <br>
        Jetzt einen dringenden Termin bei einer Gynäkologin?
        <br>
        Gyn. Ambulatorium SZB AG <a href="tel:+41323242233">032 324 22 33</a>
      </p>
      <p>
        <ul>
          <li>
            <a href="/downloads/190401_MM_Gesundheitszentrum_am_Bahnhof_SZB.pdf" target="_blank" rel="noopener">
              Infos für Medien
            </a>
          </li>
          <!-- <li>
            <a href="#">
              Infos für ÄrztInnen
            </a>
          </li>
          <li>             
            <a href="#">
              Infos für Patienten
            </a>
          </li> -->
        </ul>
      </p>
    </section>
    <section class="fr">
      <h2>Medin Bienne,
        <br>
        dès octobre 2019</h2>
      <p>
        La proximité d’un médecin de famille, les connaissances spécifiques d’un
        médecin spécialiste et de l’infrastructure hospitalière – le tout au
        même étage directement à la gare.
        <br>
        <br>
        Pour un rendez-vous urgent chez un médecin de famille: 
        <br>
        Localmed Bienne <a href="tel:+41323295500">032 329 55 00</a>  
        <br>
        <br>
        Pour un rendez-vous urgent gynécologique: 
        <br>
        Service ambulatoire de gynécologie CHB <a href="tel:+41323242233">032 324 22 33</a>

      </p>
      <p>
        <ul>
          <li>
            <a href="/downloads/190401_MM_Centre_de_sante_a_la_gare_CHB.pdf" target="_blank" rel="noopener">
              Infos pour les médias
            </a>
          </li>
          <!-- <li>
            <a href="#">
              Infos für ÄrztInnen
            </a>
          </li>
          <li>             
            <a href="#">
              Infos für Patienten
            </a>
          </li> -->
        </ul>
      </p>
    </section>
  </div>
</template>

<script>
export default {};
</script>

<style lang="stylus" scoped>
.maincontent 
  max-width: 1200px;
  margin: auto;
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