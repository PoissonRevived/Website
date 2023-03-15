<script setup lang="ts">
import Footer from "~/components/footer.vue";
</script>

<template>
  <div>
    <main>
      <header>
        <NuxtLink to="/">
          <img aria-label="Poison Revived Logo" src="~/assets/logo.png" />
        </NuxtLink>
      </header>

      <Nuxt />
      <Footer></Footer>
    </main>
  </div>
</template>

<style scoped>
main {
  display: flex;
  flex-direction: column;
  gap: 2rem;
  width: 35rem;
  margin: 0 auto;
  margin-bottom: 2rem;
}
</style>
