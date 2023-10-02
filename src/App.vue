<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <header>
    <img alt="Primate" class="logo" src="https://www.thoughtco.com/thmb/0duuyy9WHxmhjT94nRUggX0_aYU=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc()/121989315-56a006c45f9b58eba4ae8c23.jpg" width="200" height="150" />

    <div class="wrapper">
      <HelloWorld msg="soviwellons.com" />
    </div>
  </header>

  <main>
    <TheWelcome />
  </main>
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
