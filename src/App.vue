<script setup>
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
  <header>
    <img src="./assets/images/logo.png" class="w-16" />
    <nav>
      <router-link to="/home" class="mr-2">主页</router-link>
      <router-link to="/about" class="mr-2">关于</router-link>
      <router-link to="/join" class="mr-2">加入</router-link>
    </nav>
  </header>
  <router-view></router-view>
</template>

<style scoped lang="less">
header {
  display: flex;
  justify-content: space-around;
  align-items: center;
  padding: 1vw 0;
  nav {
    text-align: center;
  }
}
</style>
