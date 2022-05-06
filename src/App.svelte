<script>
  import Home from 'pages/Home.svelte';
  import { Router, Route, NotFound, redirect } from 'pager/index.js';
  import Impressum from 'components/pages/Impressum.svelte';
</script>

<Router>
  <Route path="/" component={Home}  />
  <Route
    path="/impressum"
    component={Impressum}
  />
  <NotFound />
</Router>

<style lang="scss" global>
  @use './scss/typography';
  @use './scss/spacing';
  @use './scss/general';
  @use './scss/animation';

  body {
    min-height: 100vh;
    min-height: -webkit-fill-available;
    padding: 0;
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    margin: 0;
    overflow: hidden;
    background: rgba(33, 33, 32, 1);
    // user-select: none;
    font-family: 'Montserrat', sans-serif;
    font-size: 1rem;
    line-height: 1.9;
    letter-spacing: 1.2;
    font-weight: 300;
    @media screen and (max-width: 600px) {
      font-size: 14px;
    }
  }
</style>
