<template>
  <div>
    <img src="../assets/pick-n-pay-logo.png" alt="logo" />
    <nav>
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </nav>
  </div>
  <router-view />
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<style scoped>
div {
    
}
</style>