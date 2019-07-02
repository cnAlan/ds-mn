<template>
<p>login</p>
</template>
<script>
export default {
  mounted() {
    this.$store.commit('setNavigate', 'login');
  }
}
</script>
