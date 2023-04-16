<template>
  <main class="side-scroll-be-gone">
    <router-view />
  </main>
</template>

<script>

export default {
  setup() {
    return {
    }
  }
}
</script>
<style lang="scss">
@import "./assets/scss/main.scss";

:root{
  --main-height: calc(100vh - 32px - 64px);
}

.side-scroll-be-gone{
  max-width: 100vw;
  overflow-x: hidden;
}


</style>
