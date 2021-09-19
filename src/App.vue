<template>
  <div id="app">
    <mheader v-bind:m_title="title"/>
    <mlogoLand v-bind:title="title"/>
    <sectour/>
    <!-- <secabout/> -->
  </div>
</template>

<script>
import mheader from './components/header.vue';
import mlogoLand from './components/logo_land.vue';
// import secabout from './components/sections/sec_about.vue';
import sectour from './components/sections/sec_tour.vue';

const queryString = window.location.search;
const urlParams = new URLSearchParams(queryString);
const mid = urlParams.get('museum_t')

export default {
  name: 'App',
  components: {
    mheader,
    mlogoLand,
    sectour
  },
  data() {
    return {
      title: mid
    }
  }
};
</script>

<style>
#app {
  font-family: 'Montserrat', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
</style>
