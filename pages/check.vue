<template>
<div class="check-container">
  <b-container class="text-left theme-container">
    <b-form-group
      label-class="font-weight-bold pt-0"
      class="mb-0 form-container"
    >
      <b-form-group
        label-cols-sm="2"
        label="旺旺号"
        label-align-sm="right"
        label-for="nested-city"
        class="alert-lable"
      >
        <b-form-input id="nested-city" placeholder="请输入旺旺号进行搜索"></b-form-input>
      </b-form-group>

      <b-form-group
        label-cols-sm="2"
        label-align-sm="right"
        label-for="nested-country"
      >
        <b-button variant="primary">立即搜索</b-button>
      </b-form-group>

    </b-form-group>
  </b-container>
  <b-container class="text-left theme-container">
    <b-row>
      <b-col>
        <p>人物关键词</p>
        <b-jumbotron class="mt-3 block">
          <b-badge variant="info">机械键盘87</b-badge>
          <b-badge variant="info">绿萝水培</b-badge>
          <b-badge variant="info">背包</b-badge>
          <b-badge variant="info">背包</b-badge>
          <b-badge variant="info">背包</b-badge>
          <b-badge variant="info">绿萝水培</b-badge>
          <b-badge variant="info">背包</b-badge>
          <b-badge variant="info">背包</b-badge>
          <b-badge variant="info">背包</b-badge>
          <b-badge variant="info">绿萝水培</b-badge>
          <b-badge variant="info">背包</b-badge>
          <b-badge variant="info">绿萝水培</b-badge>
          <b-badge variant="info">绿萝水培</b-badge>
          <b-badge variant="info">绿萝水培</b-badge>
          <b-badge variant="info">绿萝水培</b-badge>
          <b-badge variant="info">背包</b-badge>
          <b-badge variant="info">绿萝水培</b-badge>
        </b-jumbotron>
      </b-col>
      <b-col>
        <p>人物关键词</p>
        <b-jumbotron class="mt-3 block">
          <b-badge variant="info">机械键盘87</b-badge>
          <b-badge variant="info">绿萝水培</b-badge>
          <b-badge variant="info">背包</b-badge>
          <b-badge variant="info">背包</b-badge>
          <b-badge variant="info">背包</b-badge>
          <b-badge variant="info">绿萝水培</b-badge>
          <b-badge variant="info">背包</b-badge>
          <b-badge variant="info">背包</b-badge>
          <b-badge variant="info">背包</b-badge>
          <b-badge variant="info">绿萝水培</b-badge>
          <b-badge variant="info">背包</b-badge>
          <b-badge variant="info">绿萝水培</b-badge>
          <b-badge variant="info">绿萝水培</b-badge>
          <b-badge variant="info">绿萝水培</b-badge>
          <b-badge variant="info">绿萝水培</b-badge>
          <b-badge variant="info">背包</b-badge>
          <b-badge variant="info">绿萝水培</b-badge>
        </b-jumbotron>
      </b-col>
    </b-row>
  </b-container>
</div>
</template>
<script>
export default {
  mounted() {
    this.$store.commit('setNavigate', 'check');
  }
}
</script>
<style scoped>
p {
  margin: 0;
}
ol {
  list-style-position: inside;
}
.alert-text {
  color: red;
}
.notice {
  color: #999;
}

</style>

