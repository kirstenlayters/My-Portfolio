<script setup lang="ts">
import TheNavbar from '../components/TheNavbar.vue'
import HeroSection from '../components/HeroSection.vue'
import AboutSection from '../components/AboutSection.vue'
import AchievementsSection from '../components/AchievementsSection.vue'
import SkillsSection from '../components/SkillsSection.vue'
import ProjectsSection from '../components/ProjectsSection.vue'
import ContactSection from '../components/ContactSection.vue'
</script>

<template>
  <div>
    <TheNavbar />

    <main>
      <HeroSection />
      <AboutSection />
      <AchievementsSection />
      <SkillsSection />
      <ProjectsSection />
      <ContactSection />
    </main>

    <footer>
      <div class="container">
        <p>&copy; 2026 My Portfolio. All rights reserved.</p>
      </div>
    </footer>
  </div>
</template>
