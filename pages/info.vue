<template>
<p>info</p>
</template>
<script>
export default {
  mounted() {
    this.$store.commit('setNavigate', 'info');
  }
}
</script>
