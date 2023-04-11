<template>
  <div>
    <h1>Cart</h1>
    <div v-if="cart.length === 0">Your cart is empty</div>
    <div v-else>
      <div v-for="item in cart" :key="item.product.id">
        <h2>{{ item.product.name }}</h2>
        <p>Price: ${{ item.product.price }}</p>
        <p>Quantity: {{ item.quantity }}</p>
      </div>
      <button @click="checkout()">Checkout</button>
    </div>
  </div>
</template>

<script>
export default {
  computed: {
    cart() {
      // Get cart from Vuex store
      return this.$store.state.cart;
    }
  },
  methods: {
    checkout() {
      // Implement checkout logic
    }
  }
};
</script>
