<template>
    <main>
      <Header/>
      <Main/>
      <Footer/>
    </main>
</template>
<script>
import Header from './components/Header.vue';
import Main from './components/Main.vue';
import Footer from './components/Footer.vue';
export default {
    components:{
        Header,
        Main,
        Footer
    }
};
</script>
<style scoped>

</style>