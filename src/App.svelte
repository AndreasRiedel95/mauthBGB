<script>
  import Home from 'pages/Home.svelte';
  import { Router, Route, NotFound, redirect } from 'pager/index.js';
  import Impressum from 'components/pages/Impressum.svelte';
</script>

<Router>
  <Route path="/" component={Home} />
  <Route path="/impressum" component={Impressum} />
  <NotFound />
</Router>

<style lang="scss" global>
  @use './scss/typography';
  @use './scss/spacing';
  @use './scss/general';
  @use './scss/animation';

  body {
    min-height: 100vh;
    background-color: #000;
    padding: 0;
    width: 100%;
    margin: 0;
    font-family: 'Montserrat', sans-serif;
    font-size: 1rem;
    line-height: 1.8;
    letter-spacing: 1.2;
    font-weight: 300;
    @media screen and (max-width: 600px) {
      font-size: 14px;
    }
  }
</style>
