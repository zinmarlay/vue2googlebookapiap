<template>
  <v-app>
    <Header/>
    <v-main>
      <router-view/>
    </v-main>
    <Footer/>
  </v-app>
</template>

<script>
import Header from '@/global/Header';
import Footer from '@/global/Footer';
export default {
  components: { Header, Footer },
  name: 'App',

  data: () => ({
    //
  }),
};
</script>
