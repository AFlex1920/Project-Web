<template>
  <div id="page-wrap">
    <ProductsGrid :products="products"></ProductsGrid>
  </div>
</template>

<script>
import ProductsGrid from "../components/ProductsGrid.vue";
import { products } from "../fake-data";
export default {
  name: "ProductsPage",
  components: {
    ProductsGrid,
  },
  data() {
    return {
      products,
    };
  },
};
</script>

