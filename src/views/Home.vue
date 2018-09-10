<template>
  <div class="home">
    <HelloWorld msg="Vue.js with Vue Router/Vuex/SSR/Code-splitting" />
  </div>
</template>

<script>
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  components: {
    HelloWorld,
  },
}
</script>
