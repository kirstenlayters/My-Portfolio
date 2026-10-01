<script setup lang="ts">
import { ref } from 'vue'
import { RouterLink } from 'vue-router'

const isMenuOpen = ref(false)
</script>

<template>
  <header class="site-header" id="home-section">
    <nav class="navbar-custom" aria-label="Main navigation">
      <div class="nav-wrap">
        <RouterLink class="navbar-brand" to="/">My Portfolio</RouterLink>

        <button
          class="nav-toggle"
          type="button"
          :aria-expanded="isMenuOpen"
          aria-controls="primary-navigation-links"
          :aria-label="isMenuOpen ? 'Close navigation' : 'Open navigation'"
          @click="isMenuOpen = !isMenuOpen"
        >
          <span></span>
          <span></span>
          <span></span>
        </button>

        <div id="primary-navigation-links" class="nav-links" :class="{ 'is-open': isMenuOpen }">
          <RouterLink :to="{ path: '/', hash: '#about-section' }" @click="isMenuOpen = false">About</RouterLink>
          <RouterLink :to="{ path: '/', hash: '#achievements-section' }" @click="isMenuOpen = false">Achievements</RouterLink>
          <RouterLink :to="{ path: '/', hash: '#education-section' }" @click="isMenuOpen = false">Education</RouterLink>
          <RouterLink :to="{ path: '/', hash: '#goals-section' }" @click="isMenuOpen = false">Goals</RouterLink>
          <RouterLink :to="{ path: '/', hash: '#skills-section' }" @click="isMenuOpen = false">Skills</RouterLink>
          <RouterLink :to="{ path: '/', hash: '#project-section' }" @click="isMenuOpen = false">Projects</RouterLink>
          <RouterLink :to="{ path: '/', hash: '#contact-section' }" @click="isMenuOpen = false">Contact</RouterLink>
        </div>
      </div>
    </nav>
  </header>
</template>
