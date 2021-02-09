<template>
  <div class="customers-box">

    <CustomersCard>
      <template v-slot:picture>
        <img alt="" src="../assets/images/image-colton.jpg">
      </template>
      <template v-slot:name>Colton Smith</template>
      <template v-slot:message>
        "We needed the same printed design as the one we had ordered a week prior.
        Not only did they find the original order, but we also received it in time.
        Excellent!"
      </template>
    </CustomersCard>

    <CustomersCard>
      <template v-slot:picture>
        <img alt="" src="../assets/images/image-irene.jpg">
      </template>
      <template v-slot:name>Irene Roberts</template>
      <template v-slot:message>
        "Customer service is always excellent and very quick turn around. Completely
        delighted with the simplicity of the purchase and the speed of delivery."
      </template>
    </CustomersCard>

    <CustomersCard>
      <template v-slot:picture>
        <img alt="" src="../assets/images/image-anne.jpg">
      </template>
      <template v-slot:name>Anne Wallace</template>
      <template v-slot:message>
        "Put an order with this company and can only praise them for the very high
        standard. Will definitely use them again and recommend them to everyone!"
      </template>
    </CustomersCard>
  </div>
</template>

<script>
import CustomersCard from '@/components/CustomersCard'

export default {
  name: 'TheCustomersBox',
  components: {
    CustomersCard
  }
}
</script>

<style scoped>

</style>
