<script setup lang="ts">
import Giscus from '@giscus/vue'
</script>

<template>
  <div class="comments-container">
    <Giscus
      id="comments"
      repo="Coin-233/vitepress"
      repoId="R_kgDOMIXMWQ"
      category="General"
      categoryId="DIC_kwDOMIXMWc4Cgr8g"
      mapping="pathname"
      term="Welcome to SOFT! MOE!"
      reactionsEnabled="1"
      emitMetadata="0"
      inputPosition="top"
      theme="https://soft.moe/giscus/giscus.css"
      lang="en"
      loading="lazy"
      crossorigin="anonymous"
    />
  </div>
</template>

<style lang="scss" scoped>
.comments-container {
  max-height: 640px;
  overflow-y: scroll;

  &::-webkit-scrollbar {
    display: none;
  }
  scrollbar-width: none;
}
</style>
