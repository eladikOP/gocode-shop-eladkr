<script lang="ts">
import { defineComponent } from "vue";
import ProductCard from "./ProductCard.vue";

export default defineComponent({
  data() {
    return {};
  },
  components: { ProductCard },
});
</script>

<template>
  <section class="products">
    <ProductCard />
    <ProductCard />
    <ProductCard />
    <ProductCard />
    <ProductCard />
    <ProductCard />
    <ProductCard />
    <ProductCard />
    <ProductCard />
    <ProductCard />
    <ProductCard />
  </section>
</template>

<style scoped>
.products {
  display: flex;
  flex-wrap: wrap;
}
</style>
