<script setup lang="ts">
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
</script>

<template>
  <section class="hero">
    <h1 class="title">WCB Bakery</h1>
    <p>
      엄선된 재료와 식감이 살아 있는 빵.<br />
      매일 아침 갓 구운 빵.<br />
      빵과 함께 행복한 시간을 만끽해보세요.
    </p>
  </section>
</template>

<style>
section {
  height: 100vh;
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center center;
}

.hero {
  background-image: url(./assets/bread1.jpg);
  text-align: center;
  padding-top: 10vh;
}

.title {
  font-family: 'Dancing Script', cursive;
  font-size: 7rem;
  margin-bottom: 2rem;
}
</style>
