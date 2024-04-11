<script setup lang="ts">
// エラー画面がインデックス登録されないようにする
document.querySelector("meta[name='robots']")?.setAttribute("content", "noindex");
</script>

<template>
  <div class="notfound">
    <h1>This is a 404(not found) page</h1>
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .notfound {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
