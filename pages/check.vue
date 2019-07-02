<template>
<p>check</p>
</template>
<script>
export default {
  mounted() {
    this.$store.commit('setNavigate', 'check');
  }
}
</script>
