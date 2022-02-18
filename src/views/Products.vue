<template>
  <main class="wrapper">
    <h1>Products</h1>

    <div class="card-container">
      <ProductCard
        v-for='(product, index, icon) in inventory.slice(0,16)'
        :key="product.id"
        class="card"
        :index="index"
        :product="product"
        :addToCart="addToCart"
        :icon="icon"
      />
    </div>
  </main>

</template>

<script>
import ProductCard from '@/components/ProductCard.vue'

export default {
  props: ['inventory', 'addToCart', 'icon'],
  components: {
    ProductCard
  }
}
</script>
