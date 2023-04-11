<template>
  <div>
    <h1>Products</h1>
    <div v-for="product in products" :key="product.id">
      <h2>{{ product.name }}</h2>
      <p>Price: ${{ product.price }}</p>
      <button @click="addToCart(product)">Add to Cart</button>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      products: [
        {
          id: 1,
          name: "Product 1",
          price: 10.99
        },
        {
          id: 2,
          name: "Product 2",
          price: 19.99
        },
        {
          id: 3,
          name: "Product 3",
          price: 7.99
        }
      ]
    };
  },
  methods: {
    addToCart(product) {
      // Add product to cart
    }
  }
};
</script>
