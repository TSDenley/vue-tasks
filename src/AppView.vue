<template>
  <div class="app-view">
    <main-nav />

    <!-- Router View -->
    <router-view
      v-if="!error"
      :key="$route.fullPath"
    />
    <!-- Error Page -->
    <error-page
      v-else
    />
  </div>
</template>

<script>
import ErrorPage from '@/components/ErrorPage.vue'
import MainNav from '@/components/MainNav'

export default {
  components: {
    ErrorPage,
    MainNav,
  },

  computed: {
    error() {
      return this.$store.state.errorHandler.error
    },
  },
};
</script>
