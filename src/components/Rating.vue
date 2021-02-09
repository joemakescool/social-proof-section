<template>
  <div class="rating">

    <img v-for="n in 5" :key=n src="../assets/images/icon-star.svg" class="rating__icon" alt="*">
    <div class="rating__message">
      <slot></slot>
    </div>

  </div>
</template>

<script>
export default {
  name: 'Rating'
}
</script>

<style scoped>

</style>
