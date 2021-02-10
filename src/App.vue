<template>
  <div class="app" id="app">
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

.app {

}

</style>
