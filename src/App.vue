<template>
  <v-app>
    <!-- <v-app-bar
      app
      color="#F9A826"
      dark
    >
    <h2>
      Gabrielle Maciel
    </h2>
    
    </v-app-bar> -->

    <v-main>
      <HelloWorld/>
    </v-main>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld';

export default {
  name: 'App',

  components: {
    HelloWorld,
  },

  data: () => ({
    //
  }),
};
</script>
