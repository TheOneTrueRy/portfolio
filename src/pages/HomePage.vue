<template>
<div class="container-fluid">
  <div class="row align-items-center bg-dark elevation-1 py-2">
    <div class="col-12 col-md-5">
      <div class="fancy">
        <span class="big">Ryan Wittman</span>
      </div>
    </div>
    <div class="col-4 col-md-1 offset-md-4 text-center">
      <div class="social">
        <div class="hover">
          <a href="https://github.com/TheOneTrueRy" target="_blank" title="Visit my GitHub profile."><span class="fs-5 underline text-light">GitHub</span></a>
        </div>
      </div>
    </div>
    <div class="col-4 col-md-1 text-center">
      <div class="social">
        <div class="hover">
        <a href="https://www.linkedin.com/in/theonetruery/" target="_blank" title="Visit my LinkedIn profile."><span class="fs-5 underline text-light">LinkedIn</span></a>
        </div>
      </div>
    </div>
    <div class="col-4 col-md-1 text-center">
      <div class="social">
        <div class="hover">
        <a href="https://codeworks.prentus.co/p/ryan-wittman" target="_blank" title="Visit my Prentus profile."><span class="fs-5 underline text-light">Prentus</span></a>
        </div>
      </div>
    </div>
  </div>
  <div class="row upper-bio-bg elevation-4">
    <div class="col-12 col-md-8 d-flex">

    </div>
    <div class="col-4 d-none d-md-flex">

    </div>
  </div>
  <div class="row lower-bio-bg">

  </div>
</div>
</template>

<script>
import { gsap } from "gsap";
import { ScrollTrigger } from "gsap/ScrollTrigger";
import { onMounted } from "vue";

gsap.registerPlugin(ScrollTrigger);

export default {
  setup() {

    onMounted(() => {
    gsap.from(".fancy", {
      duration: 2,
      scale: 0.8,
      opacity: 0,
      ease: "elastic"
    })
    gsap.from(".social", {
      duration: 2,
      delay: 0.15,
      scale: 0.8,
      opacity: 0,
      stagger: 0.2,
      ease: "elastic"
    })
    gsap.from(".upper-bio-bg", {
      delay: 0.65,
      duration: 2,
      opacity: 0
    })
    })
    return {
    }
  }
}
</script>

<style scoped lang="scss">
  .fancy{
    text-align: center;
    font-family: 'Patua One', cursive;
    text-shadow: 1px 1px 0 black;
    letter-spacing: 1px;
  }

  @media screen and (min-width: 768px) {
    .fancy{
      text-align: start;
    }
    
  }

  .big{
    font-size: 2.5em;
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

  .hover:active{
    transform: scale(0.9);
  }

  .upper-bio-bg{
    height: 50vh;
    background: rgb(48,44,44);
    background: linear-gradient(90deg, rgba(48,44,44,1) 0%, rgba(255,255,255,1) 100%);
  }
</style>
