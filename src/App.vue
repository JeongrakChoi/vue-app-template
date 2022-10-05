<template>
  <Header></Header>
  <router-view></router-view>
  <Footer></Footer>
</template>

<script>
  import Header from './layout/Header';
  import Footer from './layout/Footer';

  export default {
    name: 'App',
    components: {
      Header,
      Footer
    }
  }
</script>