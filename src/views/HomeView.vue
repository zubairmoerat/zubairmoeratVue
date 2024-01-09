<template>
  <h1>Welcome</h1>
  <div class="row d-flex">
    <div class="col" v-if="Home">
      <p class="lead" v-for="title in Home" :key="title">{{ title }}</p>
    </div>
    <div class="col">
      <img src="https://drive.google.com/uc?id=1G3WJXBiXyM8o8wr1XLjRBQA2IIsjvZBr" alt="Landing" loading="lazy" class="img-fluid w-50 h-50">
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomeView',
  components: {},
  computed: {
    Home() {
      return this.$store.state.home
    }
  },
  mounted() {
    this.$store.dispatch('fetchHome')
  }
}
</script>
