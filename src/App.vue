<template>
  <div id="app">
    <router-view/>
    <TheAttribution></TheAttribution>
  </div>
</template>

<script>
import TheAttribution from '@/components/TheAttribution'

export default {
  components: {
    TheAttribution
  }
}
</script>

<style lang="scss">
@import "sass/main";

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
