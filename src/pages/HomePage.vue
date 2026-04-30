<template>
  <div class="container-fluid g-0">
    <!-- SECTION Desktop Navbar -->
    <div class="d-lg-flex align-items-center justify-content-between bg-dark elevation-1 py-3 d-none">
      <div class="d-flex">
        <div class="social">
          <div class="hover">
            <a href="https://github.com/TheOneTrueRy" target="_blank" rel="noopener noreferrer"
              class="text-light underline ms-3">
              <span class="fs-5">
                GitHub <i class="mdi mdi-github"></i>
              </span>
            </a>
          </div>
        </div>
        <div class="social">
          <span class="fs-5 text-light ms-3">
            Contact Me:
          </span>
        </div>
        <div class="social">
          <div class="hover">
            <a href="https://www.linkedin.com/in/theonetruery" target="_blank" rel="noopener noreferrer"
              class="text-light underline ms-3">
              <span class="fs-5">
                LinkedIn <i class="mdi mdi-linkedin"></i>
              </span>
            </a>
          </div>
        </div>
        <div class="social">
          <div class="hover">
            <a href="mailto:officiallyry@outlook.com" class="text-light underline ms-3">
              <span class="fs-5">
                OfficiallyRy@outlook.com <i class="mdi mdi-email"></i>
              </span>
            </a>
          </div>
        </div>
      </div>
      <div class="me-3 d-flex">
        <div class="social me-3">
          <div class="hover">
            <a href="/RyanWittmanResumePDF.pdf" class="text-light pointer underline" download>
              <span class="fs-5">
                Resume <i class="mdi mdi-download"></i>
              </span>
            </a>
          </div>
        </div>
        <div class="social">
          <div class="hover">
            <span class="fs-5 pointer underline" @click="scrollToProjects()">
              Projects <i class="mdi mdi-arrow-down"></i>
            </span>
          </div>
        </div>
      </div>
    </div>
    <!-- SECTION Mobile Navbar -->
    <div class="row d-lg-none align-items-center bg-dark py-2">
      <div class="col-12 d-flex justify-content-between px-5">
        <div class="social d-flex">
          <div class="hover">
            <a href="https://github.com/TheOneTrueRy" target="_blank" title="Visit my GitHub profile."
              ref="noopener noreferrer"><span class="fs-5 underline text-light">GitHub <i
                  class="mdi d-none d-sm-inline mdi-github"></i></span></a>
          </div>
        </div>
        <div class="social">
          <div class="hover">
            <a href="/RyanWittmanResumePDF.pdf" class="text-light pointer underline" download>
              <span class="fs-5">
                Resume <i class="mdi d-none d-sm-inline mdi-download"></i>
              </span>
            </a>
          </div>
        </div>
        <div class="social">
          <div class="hover">
            <span class="fs-5 pointer underline" @click="scrollToProjects()">
              Projects <i class="mdi d-none d-sm-inline mdi-arrow-down"></i>
            </span>
          </div>
        </div>
      </div>
      <div class="col-12 text-center">
        <div class="social mt-3">
          <span class="fs-5">
            Contact Me:
          </span>
        </div>
      </div>
      <div class="col-12">
        <div class="social d-flex">
          <div class="hover">
            <a href="https://www.linkedin.com/in/theonetruery/" target="_blank" title="Visit my LinkedIn profile."><span
                class="fs-5 underline text-light">LinkedIn <i class="mdi mdi-linkedin"></i></span></a>
          </div>
        </div>
      </div>
      <div class="col-12 pb-1">
        <div class="social d-flex">
          <div class="hover">
            <a href="mailto:OfficiallyRy@outlook.com"><span class="fs-5 underline text-light">OfficiallyRy@outlook.com
                <i class="mdi mdi-email"></i></span></a>
          </div>
        </div>
      </div>
    </div>
    <!-- SECTION Fancy Header / Upper Bio -->
    <div class="row upper-bio-bg elevation-4">
      <div class="col-12 col-lg-6 d-flex align-items-center justify-content-center">
        <div class="p-4 rounded d-flex flex-column">
          <span class="fancy">Ryan Wittman</span>
          <span class="subtitle text-light text-shadow">Developer & Designer</span>
        </div>
      </div>
      <div class="col-6 g-0 d-none d-lg-flex justify-content-end align-items-end h-100">
        <img src="/Actual-Ry.png" alt="Ryan Wittman Headshot" class="headshot">
      </div>
    </div>
    <div class="row">
      <!-- SECTION Coding Experience -->
      <div class="col-12">
        <div class="row right-to-left vh-39 border mobile-card">
          <div class="col-12 col-lg-4 g-0 elevation-2 vh-39">
            <img src="https://media.timeout.com/images/105207533/image.jpg"
              alt="Stock Image of Computer-based Office Space" class="side-image">
          </div>
          <div class="col-12 col-lg-8 vh-39 bg-dark py-3 d-flex flex-column align-items-center elevation-2">
            <span class="fs-2">Coding Experience</span>
            <span class="pt-3 my-px">&nbsp &nbsp &nbsp &nbsp In January of 2023 I started my coding journey, attending a
              13-Week long bootcamp in Boise, Idaho called <i>Boise CodeWorks</i>. Deeply knowledgeable, talented, and
              caring instructors taught and helped me in the ways of full-stack software development over a 500+ hour
              span
              of time. I'll be forever grateful for such a great change in my life! I now have a deep passion that
              enables
              me to go to work (on the code) every day excited and wanting more.</span>
            <span class="pt-2 my-px pb-2">&nbsp &nbsp &nbsp &nbsp I now have experience making over 40 projects both
              solo
              and in team settings. So far I've utilized HTML, (S)CSS, JavaScript, Vue, React, Next.js, Node, Express,
              C#,
              .NET, and Scrum/Agile methods when making my products! I am constantly on the look out for what to learn
              next in order to take my applications to the next level and give clients exactly what they dream
              of!</span>
            <span class="pt-2 my-px pb-2">&nbsp &nbsp &nbsp &nbsp From September 2024 to April 2026 I utilized all of my
              skills along with constantly learning new ones as a Full-Time App Developer for Pennant Services, a major
              Healthcare company spanning the whole USA. I proudly worked within both the front-end and back-end of the
              team constantly contributing to and managing the development and design of many major projects within the
              company simultaneously. Both my management and my fellow team-members consistently praised me not just for
              my notably high-quality work, but also the cohesion and dependability I personally brought to the
              team.</span>
          </div>
        </div>
      </div>
      <!-- SECTION Personal Life -->
      <div class="col-12">
        <div class="row left-to-right border vh-39 mobile-card">
          <div
            class="col-12 col-lg-8 vh-39 order-lg-1 order-2 bg-dark py-3 d-flex flex-column justify-content-around align-items-center elevation-2">
            <span class="fs-2">Personal Life</span>
            <span class="pt-3 my-px">&nbsp &nbsp &nbsp &nbsp I've spent nearly my entire life working with technology,
              utilizing a variety of software and gradually learning the ins and outs of them. With that has naturally
              come more technical skills for me to even count, allowing me to have an affinity for computers. Eventually
              I
              realized that software development was the natural next step, and haven't regretted it a day since!</span>
            <span class="pt-3 my-px pb-2">&nbsp &nbsp &nbsp &nbsp Throughout that time, I have always
              proudly been a gamer. Spending my free time on numerous types of video games has given me more skills and
              advantages, such as being able to naturally meld, socialize, and manage projects full of people due to all
              of my time on MMOs. My experience playing competitively on multiple shooters has also helped me develop
              elevated efficiency and attention to every little detail, even in high-stress environments.</span>
            <span id="projects" class="pt-3 my-px pb-2">&nbsp &nbsp &nbsp &nbsp The personal and developer sides of my
              life have blended at times as I ended up both using my skills to create web-based games and creating
              multiple mods across some of the video
              games I played
              in my spare time, multiple of which are featured in my projects below. Multiple of the mods I developed
              have gone on
              to have hundreds of thousands of downloads and some
              of the highest endorsements from the community and users who appreciated both the content and the
              dedication I personally had to the users of the mod and any of their feedback.</span>
          </div>
          <div class="col-12 col-lg-4 vh-39 order-lg-2 order-1 g-0 elevation-2">
            <img src="https://static2.srcdn.com/wordpress/wp-content/uploads/2020/10/gamingpc3.jpg" alt=""
              class="side-image">
          </div>
        </div>
      </div>
    </div>
    <!-- SECTION Projects -->
    <div class="row bg-dark">
      <div class="col-12 text-center d-flex flex-column pt-1 pb-5 px-4">
        <span class="fs-1">Projects:</span>
      </div>
      <div class="col-12 col-lg-10 offset-lg-1 col-xl-8 offset-xl-2 px-5 px-lg-0 pb-4 pt-1 d-flex flex-column">
        <div class="row elevation-2 rounded project-card-1 border bg-gradient bg-dark mb-2 align-items-center">
          <div class="col-12 col-lg-4 g-0 d-flex align-items-center justify-content-center vh-25 px-2">
            <a href="https://EasilySWADE.com/" target="_blank" rel="noopener noreferrer" class="px-1"
              title="Visit the EasilySWADE website!">
              <img src="https://udixydcfgbzwwnvpwubp.supabase.co/storage/v1/object/public/sandbox/God/EasilySwade.png"
                alt="" class="max">
            </a>
          </div>
          <div class="col-12 col-lg-8 d-flex flex-column p-3 pt-2 pb-4">
            <a href="https://EasilySWADE.com/" target="_blank" rel="noopener noreferrer" class="hover-link"
              title="Visit the EasilySWADE website!">
              <span class="fs-5 swade">EasilySWADE</span>
            </a>
            <span class="pt-2 fs-5 project-card-end-1">The EasilySWADE project is made to be a companion app for those
              playing the "Savage Worlds" TTRPG by Pinnacle Entertainment, often referred to as SWADE by it's community.
              My fiancee brought the idea to me as we set up our own campaign with friends and found there not being any
              "D&D Beyond"esque companion for this specific, beloved TTRPG. This is currently my main project and
              continues to be updated as frequently as possible.</span>
            <span class="pt-3"><i>(Full-Stack App made using a Node.js backend and API, MongoDb database, and a Vue 3
                frontend)</i></span>
          </div>
        </div>
      </div>
      <div class="col-12 col-lg-10 offset-lg-1 col-xl-8 offset-xl-2 px-5 px-lg-0 d-flex flex-column pb-4 pt-1">
        <div class="row elevation-2 rounded project-card-2 bg-dark bg-gradient border my-2 align-items-center">
          <div class="col-12 col-lg-4 g-0 d-flex align-items-center justify-content-center vh-25 px-2">
            <a href="https://zjduff.vercel.app/" target="_blank" rel="noopener noreferrer" class="px-2"
              title="Visit the Alice Duff Portfolio website!">
              <img src="/Alice-Logo.png" alt="" class="max">
            </a>
          </div>
          <div class="col-12 col-lg-8 d-flex flex-column p-3 pt-2 pb-4">
            <a href="https://zjduff.vercel.app/" target="_blank" rel="noopener noreferrer" class="hover-link"
              title="Visit the Alice Duff Portfolio website!">
              <span class="fs-5 alice">Alice Duff Portfolio</span>
            </a>
            <span class="pt-2 fs-5 project-card-end-2">Professional portfolio site made for a client (Alice Duff) who
              reached out to me wanting to show off their Special Effects Makeup and Assistant Director Film work on a
              quality site to potential employers.</span>
            <span class="pt-3"><i>(Front-End App using JavaScript, SCSS, HTML5, and the Vue 3 Framework)</i></span>
          </div>
        </div>
      </div>
      <div class="col-12 col-lg-10 offset-lg-1 col-xl-8 offset-xl-2 px-5 px-lg-0 d-flex flex-column pb-4 pt-1">
        <div class="row elevation-2 rounded project-card-3 bg-dark bg-gradient border my-2 align-items-center">
          <div class="col-12 col-lg-4 g-0 d-flex align-items-center justify-content-center vh-25 px-2">
            <a href="https://theonetruery.github.io/vooDoo/" target="_blank" rel="noopener noreferrer" class="px-1"
              title="Visit the Who Do You VooDoo? website!">
              <img src="/Who-Do-You-VooDoo-Logo.png" alt="" class="max">
            </a>
          </div>
          <div class="col-12 col-lg-8 d-flex flex-column p-3 pt-2 pb-4">
            <a href="https://theonetruery.github.io/vooDoo/" target="_blank" rel="noopener noreferrer"
              class="hover-link" title="Visit the Who Do You VooDoo? website!">
              <span class="fs-4 voodoo">Who Do You VooDoo?</span>
            </a>
            <span class="pt-2 fs-5 project-card-end-3">An expansive and customizable webpage clicker game that allows
              you
              to earn a currency and buy upgrades, temporary boosts, customization for what you're clicking, along with
              earning achievements through your clicking journey. Also features: A ton of custom art done by the love of
              my life. ❤️ </span>
            <span class="pt-2"><i>(Front-End App using JavaScript, SCSS, HTML5, and the Vue 3 Framework)</i></span>
          </div>
        </div>
      </div>
      <div class="col-12 col-lg-10 offset-lg-1 col-xl-8 offset-xl-2 px-5 px-lg-0 pb-4 pt-1 d-flex flex-column">
        <div class="row elevation-2 rounded project-card-4 border bg-gradient bg-dark mb-2 align-items-center">
          <div class="col-12 col-lg-4 g-0 d-flex align-items-center justify-content-center vh-25 px-2">
            <a href="https://gratuities.onrender.com/" target="_blank" rel="noopener noreferrer" class="px-1"
              title="Visit the Gratuities website!">
              <img src="/Gratuities-Logo.png" alt="" class="max">
            </a>
          </div>
          <div class="col-12 col-lg-8 d-flex flex-column p-3 pt-2 pb-4">
            <a href="https://gratuities.onrender.com/" target="_blank" rel="noopener noreferrer" class="hover-link"
              title="Visit the Gratuities website!">
              <span class="fs-5 gratuities">Gratuities</span>
            </a>
            <span class="pt-2 fs-5 project-card-end-4">Ever thought about those at a business that normally can't be
              given
              a tip for how good their work was? This <i>Concept</i> Application made by a team of 5 developers during
              their
              time at Boise CodeWorks provides a platform for
              service workers to sign up, be represented under a business if they choose, and receive direct tips &
              reviews based on their work & service.</span>
            <span class="pt-3"><i>(Full-Stack App made using a Node.js backend and API, MongoDb database, a Vue 3
                frontend, and both the QR Code & Courier APIs)</i></span>
          </div>
        </div>
      </div>
      <div class="col-12 col-lg-10 offset-lg-1 col-xl-8 offset-xl-2 px-5 px-lg-0 d-flex flex-column pb-4 pt-1">
        <div class="row elevation-2 rounded project-card-5 bg-dark bg-gradient border my-2 align-items-center">
          <div class="col-12 col-lg-4 g-0 d-flex align-items-center justify-content-center vh-25 px-2">
            <a href="https://www.nexusmods.com/oblivionremastered/mods/567" target="_blank" rel="noopener noreferrer"
              class="px-2" title="Visit the Auto Upgrade Leveled Items modpage!">
              <img src="/AULI-Logo.png" alt="" class="max">
            </a>
          </div>
          <div class="col-12 col-lg-8 d-flex flex-column p-3 pt-2 pb-4">
            <a href="https://www.nexusmods.com/oblivionremastered/mods/567" target="_blank" rel="noopener noreferrer"
              class="hover-link" title="Visit the Auto Upgrade Leveled Items modpage!">
              <span class="fs-5 auli">Auto Upgrade Leveled Items</span>
            </a>
            <span class="pt-2 fs-5 project-card-end-5">A mod made for the video game The Elder Scrolls IV: Oblivion
              Remastered. People, including
              myself and friends, had need of a mod with AULI's utility so I taught myself completely from scratch how
              to use the
              game's modding tools and papyrus scripting just to fixate for 10 hours straight and create
              the first version of AULI overnight. AULI went on to be one of the most downloaded and user-endorsed mods
              of all time for the game, providing me with a chance to provide and respond to a passionately
              user-oriented service & live product.</span>
            <span class="pt-3"><i>(In-Game mod made using the Elder Scrolls/Oblivion Creation Kit tools)</i></span>
          </div>
        </div>
      </div>
    </div>
    <div class="row bg-dark text-light text-center">
      <marquee class="w-100">
        <span class="fs-5">Made with Vue 3, SCSS, and GSAP.</span>
        <span class="fs-5 ms-2"><i class="mdi mdi-copyright"></i> 2026 Ryan Wittman.</span>
        <span class="fs-5 ms-2">(This is an ironic marquee tag I swear 😉)</span>
      </marquee>
    </div>
  </div>
</template>

<!-- SECTION Scripting -->
<script>
import { gsap } from "gsap";
import { ScrollTrigger } from "gsap/ScrollTrigger";
import { onMounted } from "vue";

gsap.registerPlugin(ScrollTrigger);

export default {
  setup() {

    onMounted(() => {
      gsap.from(".social", {
        duration: 2,
        scale: 0.8,
        opacity: 0,
        stagger: 0.2,
        ease: "elastic"
      })
      gsap.from(".upper-bio-bg", {
        delay: 0.9,
        duration: 2.2,
        opacity: 0
      })
      gsap.fromTo(".right-to-left", {
        x: 4000
      }, {
        delay: 0.8,
        duration: 1.8,
        ease: "power1.out",
        x: 0
      })
      gsap.fromTo(".left-to-right", {
        x: -4000
      }, {
        delay: 1.6,
        duration: 1.8,
        ease: "power1.out",
        x: 0
      })
      gsap.from(".project-card-1", {
        scrollTrigger: ".project-card-end-1",
        opacity: 0,
        duration: 1.1,
        scale: 0.2,
      })
      gsap.from(".project-card-2", {
        scrollTrigger: ".project-card-end-2",
        opacity: 0,
        duration: 1.1,
        scale: 0.2,
      })
      gsap.from(".project-card-3", {
        scrollTrigger: ".project-card-end-3",
        opacity: 0,
        duration: 1.1,
        scale: 0.2,
      })
      gsap.from(".project-card-4", {
        scrollTrigger: ".project-card-end-4",
        opacity: 0,
        duration: 1.1,
        scale: 0.2,
      })
      gsap.from(".project-card-5", {
        scrollTrigger: ".project-card-end-5",
        opacity: 0,
        duration: 1.1,
        scale: 0.2,
      })
    })
    return {
      scrollToProjects() {
        document.getElementById("projects").scrollIntoView();
      }
    }
  }
}
</script>

<!-- SECTION SCSS / Styling -->
<style scoped lang="scss">
.fancy {
  text-align: center;
  font-family: 'Patua One', cursive;
  text-shadow: 1px 1px 0 black;
  letter-spacing: 1px;
  font-size: 2.3em;
  color: white;
}

.my-px {
  padding-left: 1.5em;
  padding-right: 1.5em;
}

.max {
  max-width: 100%;
  max-height: 22vh;
}

.mobile-h-50 {
  height: 50%;
}

.social {
  justify-content: center;
}

.subtitle {
  font-size: 1.4em;
  font-style: italic;
}


.underline {
  border-bottom: 1px solid white;
}

.vh-25 {
  height: 25vh;
}

.hover {
  transition: 0.5s;
}

.hover:hover {
  transform: scale(1.1);
}

.hover:active {
  transform: scale(0.9);
}

.hover-link:hover {
  color: rgb(49, 100, 217);
  cursor: pointer;
  text-decoration: underline;
}

.upper-bio-bg {
  height: 35vh;
  background-image: url("/BackgroundByCy3.png");
  background-size: cover;
}

.headshot {
  height: 90%;
}

.side-image {
  height: 100%;
  width: 100%;
  object-fit: cover;
}

.vh-39 {
  min-height: 39vh;
}

.pointer {
  cursor: pointer;
}

.troop-logo {
  width: 120% !important;
  max-width: 120% !important;
}

@media screen and (min-width: 992px) {
  .fancy {
    text-align: start;
  }

  .social {
    justify-content: flex-start;
  }

  .mobile-h-50 {
    height: 37vh;
  }

  .my-px {
    padding-left: 2em;
    padding-right: 2em;
  }

  .upper-bio-bg {
    height: 45vh;
  }
}


.gratuities {
  font-family: 'Rowdies', cursive;
  color: #06d6a0;
}

.swade {
  font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  color: #da0000;
  font-weight: bold;
}

@font-face {
  font-family: 'oblivion';
  src: url('src/assets/scss/fonts/oblivion-font.ttf') format('truetype');
}

.auli {
  font-family: 'oblivion';
  color: #ffbb0a;
}

.voodoo {
  font-family: 'Zeyada', cursive;
  color: white;
  text-shadow: 0 4px 0 rgb(82, 13, 109);
  text-shadow: 0 0 4px white, 0 3px 0 rgb(64, 14, 87);
}

.alice {
  font-family: 'Jost', sans-serif;
  color: #6A50A1;
}
</style>
