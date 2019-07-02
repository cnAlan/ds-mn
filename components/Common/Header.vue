<template>
  <header>
    <ul>
      <li>
        <nuxt-link to="/">
          悟空电商
        </nuxt-link>
      </li>
      <li>
        <nuxt-link to="/">
          首页
        </nuxt-link>
      </li>
      <li>
        <nuxt-link :to="{name: 'marking'}">
          超级打标
        </nuxt-link>
      </li>
      <li>
        <nuxt-link to="/">
          批量打标
        </nuxt-link>
      </li>
      <li>
        <nuxt-link to="/">
          标签查询
        </nuxt-link>
      </li>
      <li>
        <nuxt-link to="/">
          教学视频
        </nuxt-link>
      </li>
      <li>
        <nuxt-link to="/">
          用户信息
        </nuxt-link>
      </li>
      <li>
        <nuxt-link to="/">
          登录/退出
        </nuxt-link>
      </li>
    </ul>
  </header>
</template>
<style scoped>
header {
  background: #01166f;
}
ul {
  text-align: center;
  padding: 10px 0;
  margin: auto;
}
li {
  list-style: none;
  display: inline-block;
  padding: 10px 20px;
}
a {
  color: #eee;
}
</style>

