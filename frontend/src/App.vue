
<template>
  <div class="wrapper">
    <nav>
      <router-link to="/">Home</router-link>
      <router-link to="/about">About</router-link>
      <router-link to="/products">Products</router-link>
    </nav>
  </div>

  <router-view></router-view>
</template>

<style scoped>
#teste {
  background-color: red;
  color: white;
}
</style>
