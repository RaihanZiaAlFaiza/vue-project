<script setup>
import { RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
import Bootstarp from "./components/bootstarp.vue";
</script>

<template>
  <header>


    <div class="wrapper">
      <bootstarp/>
    </div>
  </header>

  <RouterView />
</template>


