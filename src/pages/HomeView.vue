<script>
export default {
  methods: {
    goToAbout() {
      this.$router.push('/about')
    },
  },
}
</script>

<template>
  <h2>HomeView test dennis</h2>
  <cv-button @click="goToAbout">Go to About</cv-button>
  
</template>