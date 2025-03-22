<script setup>
function a() {
  console.log('1')
}
a()
function b() {
  console.log('2')
}
function c() {
  console.log('3')
}
b()
c()
function d() {
  console.log('4')
}
d()
</script>

<template>
  <h2>APP</h2>
</template>

<style scoped>
.main {
  width: 100px;
}
</style>
