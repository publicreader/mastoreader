<template>
  <v-app>
    <v-app-bar
      app
      color="#3C526A"
      dark
    >
      <div class="d-flex align-center">
        <v-img
          alt="Mastoreader Logo"
          class="shrink mr-2"
          contain
          src="./assets/mastoreader-logo.png"
          transition="scale-transition"
          width="40"
        />
      </div>

      <v-spacer></v-spacer>

      <v-btn
        href="https://github.com/Mastoreader/mastoreader"
        target="_blank"
        text
      >
        <span class="mr-2">Latest Release</span>
        <v-icon>mdi-open-in-new</v-icon>
      </v-btn>
    </v-app-bar>

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
