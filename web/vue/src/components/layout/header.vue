<template lang='pug'>
  div
    nav#mainNav.navbar.navbar-expand-lg.navbar-light.fixed-top.py-3
      .container
        a.navbar-brand.js-scroll-trigger(href='#page-top') Bot For You
        button.navbar-toggler.navbar-toggler-right(type='button' data-toggle='collapse' data-target='#navbarResponsive' aria-controls='navbarResponsive' aria-expanded='false' aria-label='Toggle navigation')
          span.navbar-toggler-icon
        #navbarResponsive.collapse.navbar-collapse
          ul.navbar-nav.ml-auto.my-2.my-lg-0
            li.nav-item
              router-link(to='/home').a.nav-link.js-scroll-trigger Home
            li.nav-item
             router-link(to='/live-gekkos').a.nav-link.js-scroll-trigger Live
            li.nav-item
              router-link(to='/backtest').a.nav-link.js-scroll-trigger Backtest
            li.nav-item
              router-link(to='/data').a.nav-link.js-scroll-trigger Local data
            li.nav-item
              router-link(to='/config').a.nav-link.js-scroll-trigger Config


</template>

<script>
export default {}
</script>

<style>
.menu {
  display: flex;
  flex-direction: row;
  margin-top: 0;
  margin-bottom: 2rem;
}

.menu a {
  flex: 1 1 100%;
  display: block;
  text-align: center;
  text-decoration: none;
  color: inherit;
}

.menu .router-link-active {
  background-color: rgba(250,250,250,.99);
}

.menu a:hover {
  text-decoration: underline;
}

</style>
