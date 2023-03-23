<script>

import AppNav from './AppNav.vue';
export default {
  name: 'AppHeader',
  components: {
    AppNav
  }
}

</script>

<template>
  <div class="container-header">
    <div class="container-logo">
      <img src="../assets/img/dc-logo.png" alt="DCLogo">
    </div>
    <div class="container-nav">
      <AppNav />
    </div>
  </div>
</template>

<style lang="scss">
.container-header {
  background-color: aqua;
  display: flex;
  padding: 1.125rem 18.75rem;
  justify-content: space-between;
  align-items: center;

  .container-logo {
    width: 50%;

  }

  .container-nav {

    list-style: none;
  }
}
</style>