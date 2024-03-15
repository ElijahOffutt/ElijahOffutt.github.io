<template>
  <v-app>
    <left />
    <right />
    <v-main>
      <router-view />
    </v-main>
  </v-app>
</template>

<script setup>
import left from './components/navs/left'
import right from './components/navs/right'
//
</script>
