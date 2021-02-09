<template>
  <div class="customers-card">
    <div class="customers-card__header-box">
      <div class="customers-card__header-box__picture">
        <slot name="picture"></slot>
      </div>

      <div class="customers-card__header-box__name">
        <p><slot name="name"></slot></p>
        <div class="customers-card__header-box__buyer"><p>Verified Buyer</p></div>
      </div>

    </div>

    <div class="customers-card__message">
      <slot name="message"></slot>
    </div>
  </div>
</template>

<script>
export default {
  name: 'CustmersCard'
}
</script>

<style scoped>

</style>
