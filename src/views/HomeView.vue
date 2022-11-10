<template>
  <div class="gradual mb-4">
    <span ref="typing"></span>
  </div>
  <div class="summary w-80 mb-8">
    <div class="pic">
      <div class="cover"></div>
    </div>
    <div class="title">
      <p class="p1 m-2">ā á ǎ à</p>
      <p class="p2 m-2">毕竟看口型这行为本身，就不是美的，只是生存本能所迫</p>
    </div>
  </div>
  <div class="summary w-80">
    <div class="pic">
      <div class="cover"></div>
    </div>
    <div class="title">
      <p class="p1 m-2">ā á ǎ à</p>
      <p class="p2 m-2">毕竟看口型这行为本身，就不是美的，只是生存本能所迫</p>
    </div>
  </div>
  <div class="summary w-80">
    <div class="pic">
      <div class="cover"></div>
    </div>
    <div class="title">
      <p class="p1 m-2">ā á ǎ à</p>
      <p class="p2 m-2">毕竟看口型这行为本身，就不是美的，只是生存本能所迫</p>
    </div>
  </div>
</template>

<script setup>
import { ref, onMounted } from "vue";
import Typed from "typed.js";

const typing = ref(null);

onMounted(() => {
  new Typed(typing.value, {
    strings: ["国有疆 生有涯 时有域 聋无界"],
    typeSpeed: 100,
    backSpeed: 30,
    loop: true,
  });
});
</script>

<style lang="less" scoped>
.gradual {
  margin-bottom: 1rem;
  font-family: QiuHong;
  font-size: 20px;
  background: -webkit-linear-gradient(315deg, #42d392 25%, #647eff, #020724);
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  text-align: center;
}
.summary {
  display: flex;
  justify-content: center;
  border: #c9cde3;
  margin: 1rem auto;
  border-style: solid;
  border-width: 1px;
  border-radius: 2%;
  .pic {
    width: 67%;
    height: 11rem;
    .cover {
      background-image: url(../assets/images/cover.jpg);
      background-size: cover;
      border-radius: 2%;
      width: 100%;
      height: 100%;
    }
  }
  .title {
    display: block;
    .p1 {
      background: -webkit-linear-gradient(
        315deg,
        #81b6f2 25%,
        #4f68e7,
        #020724
      );
      background-clip: text;
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }
    .p2 {
      color: #363636;
      font-family: QiuHong;
    }
  }
}
</style>
