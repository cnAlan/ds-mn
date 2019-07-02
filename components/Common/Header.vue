<template>
  <header>
    <ul>
      <li>
        <nuxt-link to="/">
          悟空电商
        </nuxt-link>
      </li>
      <li :class="{active: $store.state.navigate == 'home'}">
        <nuxt-link to="/">
          首页
        </nuxt-link>
      </li>
      <li :class="{active: $store.state.navigate == 'marking'}">
        <nuxt-link :to="{name: 'marking'}">
          超级打标
        </nuxt-link>
      </li>
      <li :class="{active: $store.state.navigate == 'batch'}">
        <nuxt-link :to="{name: 'batch'}">
          批量打标
        </nuxt-link>
      </li>
      <li :class="{active: $store.state.navigate == 'check'}">
        <nuxt-link :to="{name: 'check'}">
          标签查询
        </nuxt-link>
      </li>
      <li :class="{active: $store.state.navigate == 'video'}">
        <nuxt-link :to="{name: 'video'}">
          教学视频
        </nuxt-link>
      </li>
      <li :class="{active: $store.state.navigate == 'info'}">
        <nuxt-link :to="{name: 'info'}">
          用户信息
        </nuxt-link>
      </li>
      <li :class="{active: $store.state.navigate == 'login'}">
        <nuxt-link :to="{name: 'login'}">
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
li.active a {
  color: #a8a7f5;
}
</style>

