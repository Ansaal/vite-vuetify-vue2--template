<template>
  <v-app>
    <v-navigation-drawer app>
      <!-- -->
    </v-navigation-drawer>

    <v-app-bar app>
      <!-- -->
    </v-app-bar>

    <!-- Sizes your content based upon application components -->
    <v-main>

      <!-- Provides the application the proper gutter -->
      <v-container fluid>

        <!-- If using vue-router -->
       <v-btn @click="counter++">{{counter}}</v-btn>
      </v-container>
    </v-main>

    <v-footer app>
      <!-- -->
    </v-footer>
  </v-app>
</template>

<script setup lang="ts">

import {ref} from "@vue/composition-api";

const counter = ref(0);


</script>



<style>
body {
  font-family: Roboto, sans-serif;
}

</style>
