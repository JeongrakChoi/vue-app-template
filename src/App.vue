<template>
  <div id="app">
    <Header></Header>
    <router-view></router-view>
    <Footer></Footer>
    <Example></Example>
  </div>
</template>

<script>
  import Header from './layout/Header';
  import Footer from './layout/Footer';
  import Example from './components/Example';

  export default {
    name: 'App',
    components: {
      Header,
      Footer,
      Example
    }
  }
</script>