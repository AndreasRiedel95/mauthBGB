<script>
</script>

<div class="height-100 width-100">
  <div class="hero-image">
    <div class="hero-headline text-center font-weight-bold mb-20 ">
      MAUTH11 BGB
    </div>
    <div class="hero-subheadline">
      Das offizielle Mauthstr. 11 Beerpong Gesetzbuch der geilsten WG
      Ingolstadts
    </div>
  </div>
  <div class="main pt-100 pb-70 pr-50 pl-50">
    <div class="display-flex main-text mb-80">
      Kennt ihr das? Ihr seid auf einer Party am Bierpong spielen, alles
      chillig, alles cool. Auf einmal folgender Spielzug: 2x Bitch Cup, Balls
      Back, Rebound Treffer, 1 Spieler on Fire, Re-rack: Formation Illuminati.
      Ihr blickt nicht mehr durch? Nicht verzagen, dafür gibt es jetzt das:
    </div>
    <div
      class="display-flex flex-direction-column justify-content-center align-items-center pt-20 pb-20"
    >
      <img src="/images/mauthrules.png" alt="MauthBGB" />
    </div>
    <div class="display-flex disclaimer main-text mb-20 mt-50 font-italic">
      Disclaimer: Wir garantieren nicht dafür, dass das MAUTH11 BGB Streitereien
      im Bierpong-Match-Verlauf ausschließt. Die Mauthstraße 11 ist nicht
      verantwortlich für etwaige Kündigungen von Freundschaften, Schlägerein,
      Misshandlung von Bierpongtischen, Verlust von Decathlon Bällen und/ oder
      das Durchbrechen von Promillegrenzen. Spielteilnahme erst ab 16 Jahren.
      Bierpong kann süchtig machen.
    </div>
    <div class="displa-flex text-blue text-center mt-50 font-weight-bold">
      &#8594;
      <a
        class="text-blue text-center "
        href="https://www.kenn-dein-limit.de"
        target="_blank"
      >
        https://www.kenn-dein-limit.de
      </a>
      &#8592;
    </div>
    <a class="impressum text-center mt-50" href="/impressum">Impressum</a>
  </div>
</div>

<style lang="scss">
  .hero-image {
    background-image: linear-gradient(
        180deg,
        rgba(0, 0, 0, 0.5) 0%,
        rgba(0, 0, 0, 0.2) 100%
      ),
      url('/images/group_mauth.jpg');
    height: 650px;
    background-position: center center;
    background-repeat: no-repeat;
    background-size: cover;
    position: relative;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    @media screen and (max-width: 500px) {
      height: 425px;
    }
  }
  .main {
    width: 100%;
    height: auto;
    margin-left: auto;
    margin-right: auto;
    display: flex;
    flex-direction: column;
  }

  .hero-headline {
    font-size: 50px;
    font-family: 'Alfa Slab One', cursive;
    font-weight: 400;
    -webkit-text-stroke-width: 1px;
    letter-spacing: 6px;
    z-index: 100;
    color: #fff;
    position: relative;
    &::after {
      content: '';
      position: absolute;
      width: 105%;
      height: 25px;
      z-index: -1;
      background-color: #5ec2e4;
      bottom: 15%;
      left: -50%;
      transform: translateX(45%);
      @media screen and (max-width: 500px) {
        height: 14px;
      }
    }
    @media screen and (max-width: 500px) {
      font-size: 28px;
    }
  }

  .hero-subheadline {
    color: #fff;
    max-width: 400px;
    width: 100%;
    margin-left: auto;
    margin-right: auto;
    line-height: 1.5;
    font-size: 18px;
    text-align: center;
    @media screen and (max-width: 500px) {
      font-size: 15px;
      max-width: 300px;
    }
  }

  .main-text {
    color: #fff;
    max-width: 700px;
    width: 100%;
    margin-left: auto;
    margin-right: auto;
  }

  img {
    width: 100%;
    max-width: 1000px;
    object-fit: contain;
  }

  .disclaimer {
    font-size: 12px;
  }
  .impressum {
    color: #fff;
    font-size: 8px !important;
  }

  .text-blue {
    color: #5ec2e4;
  }
</style>
