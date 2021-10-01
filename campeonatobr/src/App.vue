<template>
  <v-app>
    <div>
      <v-app-bar color="green darken-4" dark>
        <v-app-bar-nav-icon @click="drawer = true"></v-app-bar-nav-icon>

        <v-toolbar-title>Campeonato Brasileiro ⚽</v-toolbar-title>
      </v-app-bar>

      <v-spacer></v-spacer>
    </div>
    <v-main>
      
      <Inicio />
      <AppTopBar />
    </v-main>
  </v-app>
</template>

<script>
import Inicio from "./components/Inicio.vue";
import AppTopBar from "./components/shared/AppTopBar.vue";

export default {
  name: "App",

  components: {
    Inicio,
    AppTopBar,
  },

  data: () => ({
    drawer: false,
    group: null,
  }),
};
</script>
