<template>
  <v-app>
    <v-app-bar
      app
      color="primary"
      dark
    >
      <div class="d-flex align-center">
        <h1>JA.K Warehouse</h1>
      </div>
      
        <v-btn icon="mdi-heart"></v-btn>

        <v-btn icon="mdi-magnify"></v-btn>

        <v-btn icon="mdi-dots-vertical"></v-btn>
    </v-app-bar>

    <v-main>
      <DashBoard/>
    </v-main>
  </v-app>
</template>

<script>
//import HelloWorld from './components/HelloWorld';
import DashBoard from './components/DashBoard';

export default {
  name: 'App',

  components: {    
//    HelloWorld,
    DashBoard
  },

  data: () => ({
    //
  }),
};
</script>
