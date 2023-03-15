<script setup lang="ts">
import Footer from "~/components/footer.vue";
</script>

<template>
  <article class="content-flex flex-column gap-_5rem">
    <header>
      <p class="text-align-center">
        Poisson Revived is a complete revival of Poisson. An early Prototype of Transformice which has been lost since
        2011 but recently found by Taikohhh and iPedroLB.
      </p>
    </header>

    <ol class="download-links">
      <li>
        <a
          href="https://github.com/PoissonRevived/Standalone/releases/download/v1.0.0/Poisson-v1.0.0-Windows.exe"
          class="button"
          >Windows (x86)</a
        >
      </li>
      <li>
        <a
          href="https://github.com/PoissonRevived/Standalone/releases/download/v1.0.0/Poisson-v1.0.0-Linux.AppImage"
          download
          class="button"
          >Linux (AppImage)</a
        >
      </li>
      <li>
        <a href="https://play.poissonrevived.xyz/" target="_blank" class="button">Web Browser (Flash Player)</a>
      </li>
      <li>
        <a href="#" class="button disabled">macOS</a>
      </li>
    </ol>
  </article>
</template>

<style scoped>
.download-links {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  gap: 0.75rem;
  justify-content: center;
}
</style>
