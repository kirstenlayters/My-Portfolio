<template>
  <div>
    <h2>Projects!</h2>
    <section id="project-section" class="projects-grid">
      <a class="project-card-link" href="https://kirstenlayters.github.io/Gallery/" target="_blank" rel="noopener noreferrer">
        <div class="project-card">
          <img
            src="/Gallery-website.png"
            alt="Gallery website preview"
            class="project-card-image"
          />
          <div class="project-card-content">
            <h2>A Gallery website</h2>
          </div>
        </div>
      </a>

      <a class="project-card-link" href="https://kirstenlayters.github.io/bootstrap-/" target="_blank" rel="noopener noreferrer">
        <div class="project-card">
          <img
            src="/Shopping-website.png"
            alt="Demo shopping website preview"
            class="project-card-image"
          />
          <div class="project-card-content">
            <h2>A demo shopping website</h2>
          </div>
        </div>
      </a>

      <a class="project-card-link" href="https://kirstenlayters.github.io/exercise-3-week-2" target="_blank" rel="noopener noreferrer">
        <div class="project-card">
          <img
            src="/recipes.png"
            alt="Recipes website preview"
            class="project-card-image"
          />
          <div class="project-card-content">
            <h2>A recipes website</h2>
          </div>
        </div>
      </a>

    </section>

    <div class="projects-action">
      <RouterLink class="primary-btn" to="/projects">View more projects</RouterLink>
    </div>
  </div>
</template>

<script setup lang="ts">
import { RouterLink } from 'vue-router'
</script>
