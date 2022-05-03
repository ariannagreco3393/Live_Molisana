<template>
  <div id="app">
    <SiteHeader/>
    <SiteMain/>
    <SiteFooter/>
  </div>
</template>

<script>
import SiteHeader from '@/components/headerComponent.vue'
import SiteMain from '@/components/mainComponent.vue'
import SiteFooter from '@/components/footerComponent.vue'


export default {
  name: 'App',
  components: {
    SiteHeader,
    SiteFooter,
    SiteMain
  }
}
</script>

<style lang="scss">


/* utility classes */
@import '@/assets/sass/_common.scss';


.text-center {
  text-align: center;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
}


main {
  background-image: url('@/assets/img/fondo-pag-speciali.jpg');
  background-size: cover;
  min-height: 50vh ;
  padding-bottom: 2rem;

  h1{
    padding: 2rem 0;
    text-align: center;
  }
}


@import '@/assets/sass/_grid_system.scss'
</style>
