<template>
  <div class="box">
    <h1>测试commit</h1>
  </div>
</template>

<script setup lang="ts">
for (let i = 0; i < 100; i++) {
  console.log(i)
}
</script>

<style scoped>
.box {
  width: 600px;
  height: 400px;
  background: black;
  h1 {
    color: white;
  }
}
</style>
