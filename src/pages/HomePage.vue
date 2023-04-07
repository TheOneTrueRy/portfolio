<template>
<div class="container-fluid">
  <div class="row align-items-center bg-dark elevation-1 py-3">
    <!-- <div class="col-12 col-md-5">
      <div class="fancy">
        <span class="big">Ryan Wittman</span>
      </div>
    </div> -->
    <div class="col-6 col-md-3 col-lg-2 ps-4">
      <div class="social d-flex">
        <div class="hover">
          <a href="https://github.com/TheOneTrueRy" target="_blank" title="Visit my GitHub profile."><span class="fs-5 underline text-light">GitHub <i class="mdi mdi-github"></i></span></a>
        </div>
      </div>
    </div>
    <div class="col-6 col-md-3 col-lg-2">
      <div class="social d-flex">
        <div class="hover">
        <a href="https://www.linkedin.com/in/theonetruery/" target="_blank" title="Visit my LinkedIn profile."><span class="fs-5 underline text-light">LinkedIn <i class="mdi mdi-linkedin"></i></span></a>
        </div>
      </div>
    </div>
    <!-- <div class="col-4 col-md-2 text-center">
      <div class="social">
        <div class="hover">
        <a href="https://codeworks.prentus.co/p/ryan-wittman" target="_blank" title="Visit my Prentus profile."><span class="fs-5 underline text-light">Prentus</span></a>
        </div>
      </div>
    </div> -->
    <div class="col-12 col-md-4 col-lg-3">
      <div class="social d-flex">
        <div class="hover">
          <a href="mailto:OfficiallyRy@outlook.com"><span class="fs-5 underline text-light">OfficiallyRy@outlook.com <i class="mdi mdi-email"></i></span></a>
        </div>
      </div>
    </div>
  </div>
  <div class="row upper-bio-bg elevation-4">
    <div class="col-12 col-md-6 d-flex align-items-center justify-content-center bingbong">
      <div class="p-4 rounded d-flex flex-column">
        <span class="fancy">Ryan Wittman</span>
        <span class="subtitle text-light text-shadow">Designer & Developer</span>
      </div>
    </div>
    <div class="col-6 g-0 d-none d-md-flex justify-content-end align-items-end h-100">
      <img src="Actual-Ry.png" alt="Ryan Wittman Headshot" class="headshot">
    </div>
  </div>
  <div class="row d-none d-md-flex">
    <div class="col-12">
      <div class="row right-to-left">
        <div class="col-4 g-0 elevation-2">
          <img src="https://media.timeout.com/images/105207533/image.jpg" alt="" class="side-image">
        </div>
        <div class="col-8 bg-dark border px-5 py-3 d-flex flex-column justify-content-start align-items-center elevation-2">
          <span class="fs-3 pt-1">Coding Experience</span>
          <span class="pt-4 px-5">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quidem rerum veniam numquam eum? Nobis quam vero modi! Quis accusantium in impedit, ducimus dignissimos repudiandae sapiente et alias aliquid. Deleniti, nemo.</span>
        </div>
      </div>
    </div>
    <div class="col-12">
      <div class="row left-to-right">
        <div class="col-8 bg-dark border px-5 py-3 d-flex flex-column justify-content-start align-items-center elevation-2">
          <span class="fs-3 pt-1">Personal Life</span>
          <span class="pt-4 px-5">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quidem rerum veniam numquam eum? Nobis quam vero modi! Quis accusantium in impedit, ducimus dignissimos repudiandae sapiente et alias aliquid. Deleniti, nemo.</span>
        </div>
        <div class="col-4 g-0 elevation-2">
          <img src="https://static2.srcdn.com/wordpress/wp-content/uploads/2020/10/gamingpc3.jpg" alt="" class="side-image">
        </div>
      </div>
    </div>
  </div>
  <div class="row d-md-none">

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
      delay: 0.7,
      duration: 2.2,
      opacity: 0
    })
    gsap.fromTo(".right-to-left", {
      x: 4000
    }, {
      delay: 1,
      duration: 2,
      ease: "power1.out",
      x: 0
    })
    gsap.fromTo(".left-to-right", {
      x: -4000
    }, {
      delay: 2,
      duration: 2,
      ease: "power1.out",
      x: 0
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
    font-size: 2.3em;
    color: white;
  }

  .social{
    justify-content: center;
  }

  .subtitle{
    font-size: 1.4em;
    font-style: italic;
  }

  @media screen and (min-width: 768px) {
    .fancy{
      text-align: start;
    }

    .social{
      justify-content: flex-start;
    }
    
  }

  .underline{
    border-bottom: 1px solid white;
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
    height: 45vh;
    // background: rgb(48,44,44);
    // background: linear-gradient(90deg, rgba(48,44,44,1) 0%, rgba(255,255,255,1) 100%);
    background-image: url("BackgroundByCy3.png");
    background-size: cover;
  }

  .headshot{
    height: 90%;
  }

  .side-image{
    height: 35vh;
    width: 100%;
    object-fit: cover;
  }
</style>
