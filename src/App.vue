<template>
  <datepicker />
</template>
<script setup lang="ts">
import { Vue, Options } from "vue-class-component";
import Datepicker from "../src/datepicker/Datepicker.vue";

export default class App extends Vue {}
</script>
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
