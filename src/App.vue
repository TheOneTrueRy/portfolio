<template>
  <main>
    <router-view />
  </main>
  <footer class="bg-dark text-light text-center">
    <marquee class="vw-100">
      <span class="fs-5">Made with Vue 3 and SCSS.</span>
      <span class="fs-5 ms-2"><i class="mdi mdi-copyright"></i> 2023 Ryan Wittman</span>
    </marquee>
  </footer>
</template>

<script>
import { computed } from 'vue'
import { AppState } from './AppState'
import Navbar from './components/Navbar.vue'

export default {
  setup() {
    return {
      appState: computed(() => AppState)
    }
  },
  components: { Navbar }
}
</script>
<style lang="scss">
@import "./assets/scss/main.scss";

:root{
  --main-height: calc(100vh - 32px - 64px);
}


footer {
  display: grid;
  place-content: center;
  // height: 32px;
}
</style>
