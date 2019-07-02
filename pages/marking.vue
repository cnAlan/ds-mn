<template>
  <div class="theme-container mt-3">
      <b-form-group
        label-class="font-weight-bold pt-0"
        class="mb-0"
      >
        <b-form-group
          label-cols-sm="2"
          label="旺旺号"
          label-align-sm="right"
          label-for="nested-city"
        >
          <b-form-input id="nested-city"></b-form-input>
        </b-form-group>

        <b-form-group
          label-cols-sm="2"
          label="商品地址"
          label-align-sm="right"
          label-for="nested-state"
        >
          <b-form-input id="nested-state" placeholder="商品的淘宝地址：http://xxx"></b-form-input>
        </b-form-group>

        <b-form-group
          label-cols-sm="2"
          label="搜索关键词"
          label-align-sm="right"
          label-for="nested-country"
        >
          <b-form-input id="nested-country" placeholder="关键词需存在于宝贝标题中"></b-form-input>
        </b-form-group>

        <b-form-group
          label-cols-sm="2"
          label-align-sm="right"
          label-for="nested-country"
        >
          <b-button variant="primary">提交</b-button>
        </b-form-group>

      </b-form-group>

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
  </div>
</template>
<script>
export default {
  data() {
    return {

    }
  },
  methods: {

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
