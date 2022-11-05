<script setup>
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
  <header>
    <img src="./assets/images/logo.png" />
    <nav>
      <router-link to="/home">主页</router-link>
      <router-link to="/about">关于</router-link>
      <router-link to="/join">加入</router-link>
    </nav>
  </header>
  <router-view></router-view>
</template>

<style scoped lang="less">
header {
  display: flex;
  justify-content: space-around;
  align-items: center;
  padding: 0.55em 0;
  img {
    width: 2.5rem;
  }
  nav {
    text-align: center;
  }
}
</style>
