<template lang="html">
  <nav class="main-nav">
    <router-link to="/">Home</router-link>
    <router-link to="/about">About</router-link>
  </nav>
</template>

<script>
export default {
}
</script>

<style lang="scss">
.main-nav {
  margin-top: 1em;
  margin-bottom: 1em;

  a {
    display: inline-block;
    margin-left: 1em;
    margin-right: 1em;
  }
}
</style>
