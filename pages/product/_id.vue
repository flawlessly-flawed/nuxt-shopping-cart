<template>
  <div>
    <h1>{{ product.name }}</h1>
    <p>Price: ${{ product.price }}</p>
    <button @click="addToCart(product)">Add to Cart</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      product: null
    };
  },
  async asyncData({ params }) {
    const response = await fetch(`https://yourapi.com/products/${params.id}`);
    const product = await response.json();
    return { product };
  },
  methods: {
    addToCart(product) {
      // Add product to cart
    }
  }
};
</script>
