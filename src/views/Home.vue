<template>
  <div class="home">
    <TheHeaderBox></TheHeaderBox>
    <TheRatingBox></TheRatingBox>
    <TheCustomersBox></TheCustomersBox>
  </div>
</template>

<script>
// @ is an alias to /src
import TheHeaderBox from '@/components/TheHeaderBox'
import TheRatingBox from '@/components/TheRatingBox'
import TheCustomersBox from '@/components/TheCustomersBox'

export default {
  name: 'Home',
  components: {
    TheHeaderBox, TheRatingBox, TheCustomersBox
  }
}
</script>
