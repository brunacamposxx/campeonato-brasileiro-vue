<template>
  <v-app>
    <HeaderApp />
    <MainPage/>
  </v-app>
</template>

<script>
import MainPage from './components/MainPage';
import HeaderApp from './components/shared/HeaderApp';

export default {
  name: 'App',

  components: {
    MainPage,
    HeaderApp,
  },

  data: () => ({
    //
  }),
};
</script>
