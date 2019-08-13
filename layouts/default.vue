<template>
  <div>
    <Header></Header>
    <nuxt />
    <Footer></Footer>
  </div>
</template>
<script>
  import Footer from '../components/common/footer'
  import Header from '../components/common/header'
  export default {
    name: 'layout',
    components: {
      Footer,
      Header
    }
  }
</script>
<style lang="scss">
	@import "../assets/styles/index.scss";
</style>
