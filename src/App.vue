<template>
  <div id="app">
    <Title/>
    <Header/>
    <router-view/>
    <Footer/>
  </div>
</template>

<script>
import Title from '@/components/Title.vue';
import Header from '@/components/Header.vue';
import Footer from '@/components/Footer.vue';

export default {
  name: 'app',
  components: { Title, Header, Footer },
};
</script>


<style lang="scss">
@import './scss/styles.scss';
@import '../node_modules/bootstrap/scss/bootstrap.scss';
</style>
