<template>
  <router-view/>
  <div id="app">
    <Navbar/>
    <section id="home">
      <HomeComp/>
    </section>
    <section id="about">
      <AboutComp/>
    </section>
    <section id="education">
      <EducationComp/>
    </section>
    <section id="projects">
      <ProjectsComp/>
    </section>
    <section id="contact">
      <ContactComp/>
    </section>
    <Footer/>
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue';
import HomeComp from './views/HomeComp.vue';
import AboutComp from './views/AboutComp.vue';
import EducationComp from './views/EducationComp.vue';
import ProjectsComp from './views/ProjectsComp.vue';
import ContactComp from './views/ContactComp.vue';
import Footer from './components/Footer.vue';

export default {
  components: {
    Navbar,
    HomeComp,
    AboutComp,
    EducationComp,
    ProjectsComp,
    ContactComp,
    Footer
  }
}
</script>
<style>
#app {
  font-family: "Poppins", serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}
body{
  margin: 0;
  scroll-behavior: smooth;
}
</style>
