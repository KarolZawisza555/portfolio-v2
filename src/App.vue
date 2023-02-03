<template>
  <v-app>
    <v-main class="main">
      <v-parallax src="https://cdn.vuetifyjs.com/images/backgrounds/vbanner.jpg">
        <NavBar />
        <v-row class="text-center ma-0">
          <AboutMeSection id="about-me" />
          <WellcomeSection id="skills" />
          <ProjectsSection id="projects" />
          <ExperienceSection id="experience" />
        </v-row>
      </v-parallax>
      <FooterBar />
    </v-main>
  </v-app>
</template>

<script setup>
import NavBar from '@/components/NavBar.vue'
import ExperienceSection from '@/components/ExperienceSection.vue'
import AboutMeSection from '@/components/AboutMeSection.vue'
import WellcomeSection from '@/components/WellcomeSection.vue'
import ProjectsSection from '@/components/ProjectsSection.vue'
import FooterBar from '@/components/FooterBar.vue'
import 'animate.css';

</script>
<style >
.main {
  background-color: #1867c0;
}
</style>
