<template>
  <div class="home">
    <Navbar></Navbar>
      <Logo/>
      <products-list></products-list>

      
      <login></login>

      <mini-cart></mini-cart>

  </div>
</template>

<script>
// @ is an alias to /src
import Logo from "@/components/Logo.vue";
import Products from "@/sections/Products.vue";
import Login from "@/components/Login.vue";

export default {
  name: 'home',
  components: {
    Logo,Products,Login

  }
}
</script>
<style>
</style>
