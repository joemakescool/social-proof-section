<template>
  <div class="ratings-box">
    <Rating>
      Rated 5 Stars in Reviews
    </Rating>

    <Rating>
      Rated 5 Stars in Report Guru
    </Rating>

    <Rating>
      Rated 5 Stars in BestTech
    </Rating>
  </div>
</template>

<script>
import Rating from '@/components/Rating'

export default {
  name: 'TheRatingBox',
  components: {
    Rating
  }
}
</script>

<style scoped>

</style>
