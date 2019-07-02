<template>
  <b-container class="text-left theme-container">
    <b-form-group
      label-class="font-weight-bold pt-0"
      class="mb-0 form-container"
    >
      <b-form-group
        label-cols-sm="2"
        label="搜索关键词"
        label-align-sm="right"
        label-for="nested-city"
        class="alert-lable"
      >
        <b-form-input id="nested-city" placeholder="关键词"></b-form-input>
      </b-form-group>

      <b-form-group
        label-cols-sm="2"
        label="淘宝商品ID"
        label-align-sm="right"
        label-for="nested-state"
        class="alert-lable"
      >
        <b-form-input id="nested-state" placeholder="淘宝商品ID"></b-form-input>
      </b-form-group>

      <b-form-group
        label-cols-sm="2"
        label="淘宝会员名"
        label-align-sm="right"
        label-for="nested-country"
        class="alert-lable"
      >
        <b-form-textarea
          id="textarea"
          v-model="text"
          placeholder="请输入淘宝会员名"
          rows="3"
          max-rows="6"
        ></b-form-textarea>
      </b-form-group>

      <b-form-group
        label-cols-sm="2"
        label-align-sm="right"
        label-for="nested-country"
      >
        <b-button variant="primary">打标</b-button>
      </b-form-group>


      <b-form-group
        label-cols-sm="2"
        label-align-sm="right"
        label-for="nested-country"
      >
        <b-alert show variant="warning">
          <p><span class="notice">功能说明：</span><span class="alert-text">首页高权重深度精准标签，可维持首页排名10天左右</span></p>
          <ol>
            <li>能够精准定位宝贝所在，利用标题任意关键词组合，让打标旺旺号通过关键词搜索能够实现宝贝首页排名。</li>
            <li>发布<span class="alert-text">定制类</span>宝贝链接，打标任务成功之后，关键词搜索里面一定要有定制二字。例如：<span class="alert-text">个性画册定制，工服定制，定制t恤</span></li>
            <li>打标任务执行之后，请耐心等待1-3分钟再操作哟！成功率100%
              <p>（关键词PC排名超过80页的可能搜索不到、降权链接无法打标成功）</p>
            </li>
          </ol>
        </b-alert>
      </b-form-group>

    </b-form-group>
  </b-container>
</template>
<script>
export default {
  mounted() {
    this.$store.commit('setNavigate', 'batch');
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
.form-container {
  width: 100%;
}
</style>

