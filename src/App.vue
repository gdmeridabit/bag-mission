<template>
  <v-app>
    <v-content>
      <Home/>
      <Bags/>
    </v-content>
  </v-app>
</template>

<script>
import Home from './components/Home';
import Bags from './components/Bags';

export default {
  name: 'App',
  components: {
    Home,
      Bags,
  },
  data: () => ({
    //
  }),
};
</script>
