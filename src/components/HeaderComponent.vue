<script setup>

</script>

<template>
  <div class="header">
    <router-link to="/"> Main page </router-link>
<!--    EXAMPLE -->
    <router-link to="/IdealGas"> Ideal Gas Simulation </router-link>
    <router-link to="/TwoGas"> Mixture of gases </router-link>
  </div>
</template>

<style scoped>
.header {
  position: absolute;
  right: 0;
  top: 0;
  padding: 10px;
  background-color: #f1f1f1;
  border-radius: 0 0 0 10px;
}
</style>
