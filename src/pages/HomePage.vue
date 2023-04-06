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
  <div class="row upper-bio-bg bg-gradient">

  </div>
  <div class="row"></div>
</div>
</template>

<script>
import { gsap } from "gsap";
import { ScrollTrigger } from "gsap/ScrollTrigger";

gsap.registerPlugin(ScrollTrigger);

export default {
  setup() {
    return {
      
    }
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

  .upper-bio-bg{
    height: 40vh;
    background-color: rgb(183, 28, 59);
  }
</style>
