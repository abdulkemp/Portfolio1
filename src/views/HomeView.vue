<template>
  <div>
    <NavBar />
    <HomeC />
    <About />
    <Education />
    <Projects />
    <Testimonials />
    <Contact />
    <Footer />
  </div>
</template>

<script>
import About from "../components/About.vue";
import NavBar from "@/components/NavBar.vue";
import HomeC from "@/components/HomeC.vue";
import Testimonials from "@/components/Testimonials.vue";
import Education from "@/components/Education.vue";
import Projects from "@/components/Projects.vue";
import Contact from "@/components/Contact.vue";
import Footer from "@/components/Footer.vue";
export default {
  name: "Home",
  components: {
    NavBar,
    HomeC,
    About,
    Testimonials,
    Education,
    Projects,
    Contact,
    Footer
  },
};
</script>

<style>
.home {
  min-height: 100vh;
  /* background-color: blue; */
  display: flex;
  justify-content: center;
  align-items: center;
}
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.homepage {
  display: flex;
  align-items: center;
}

.home-img {
  padding-left: 5rem;
}

.home-img img {
  border-radius: 40% 60% 48% 52% / 57% 45% 55% 43%;
  width: 20rem;
}

.home-brief {
  font-family: "Trebuchet MS", "Lucida Sans Unicode", "Lucida Grande",
    "Lucida Sans", Arial, sans-serif;
}

.con-btn {
  width: 10rem;
  height: 3rem;
  margin-top: 1rem;
  background-color: rgb(133, 128, 128);
  color: whitesmoke;
}

.con-btn:hover {
  background-color: black;
  color: white;
  cursor: pointer;
}
</style>

<!-- <template>
  <div>
    <NavBar />
  </div>
</template>

<script>
import NavBar from '@/components/NavBar.vue'
import About from '../components/About.vue'
import Home from '../components/Home.vue'
  export default {
    name: 'HomeView',
    components: {
      NavBar,
      Home,
      About,
      Testimonials,
      Education,
      Projects,
      Contact,
    }
  }
</script>

<style>

</style> -->