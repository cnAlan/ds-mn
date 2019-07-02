<template>
  <div>
    <Header />
    <nuxt />
  </div>
</template>

<script>
import Header from '../components/Common/Header'
import "../assets/global.css"
export default {
  components: {
    Header
  }
}
</script>
