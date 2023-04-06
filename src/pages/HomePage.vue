<template>
<div class="container-fluid">
  <div class="row align-items-center bg-dark elevation-1">
    <div class="col-12 col-md-5">
      <span class="fs-1 fancy">Ryan Wittman</span>
    </div>
    <div class="col-4 col-md-1 offset-md-4 text-center">
      <a href="https://github.com/TheOneTrueRy" target="_blank" class="hover" title="Visit my GitHub profile."><span class="fs-5 underline text-light">GitHub</span></a>
    </div>
    <div class="col-4 col-md-1 text-center">
      <a href="https://www.linkedin.com/in/theonetruery/" target="_blank" class="hover" title="Visit my LinkedIn profile."><span class="fs-5 underline text-light">LinkedIn</span></a>
    </div>
    <div class="col-4 col-md-1 text-center">
      <a href="https://codeworks.prentus.co/p/ryan-wittman" target="_blank" class="hover" title="Visit my Prentus profile."><span class="fs-5 underline text-light">Prentus</span></a>
    </div>
  </div>
</div>
</template>

<script>
export default {
  setup() {
    return {}
  }
}
</script>

<style scoped lang="scss">
  .fancy{
    font-family: 'Patua One', cursive;
    text-shadow: 1px 1px 0 black;
    letter-spacing: 1px;
  }

  .underline{
    text-decoration: underline;
  }

  .hover{
    transition: 0.5s;
  }

  .hover:hover{
    transform: scale(1.1);
  }
</style>
