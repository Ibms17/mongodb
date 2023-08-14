<template>
  <div id="nav-bar">
    <router-link :to="{ name: 'product' }" id="products-link">Product</router-link>
    <router-link :to="{ name: 'cart' }" id="cart-link">
      <button>Cart</button>
    </router-link>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
#nav-bar {
  border-bottom: 1px solid #ddd;
  height: 75px;
  width: 100%;
}
#products-link {
  text-align: center;
  display: block;
  color: #41b883;
  font-size: 22px;
  left: 32px;
  position: absolute;
  top: 16px;
  text-decoration: none;
}
#products-link h1 {
  margin: 0;
}
#cart-link {
  position: absolute;
  right: 16px;
  top: 16px;
}
button {
  background-color: #41b883;
  border: none;
  border-radius: 8px;
  color: white;
  cursor: pointer;
  font-size: 16px;
  font-weight: bold;
  outline: 0;
  padding: 16px;
}
</style>
