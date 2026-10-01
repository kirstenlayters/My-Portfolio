<script setup lang="ts">
import TheNavbar from '../components/TheNavbar.vue'
</script>

<template>
  <div>
    <TheNavbar />

    <main class="projects-page">
      <section class="projects-page-intro" aria-labelledby="projects-page-title">
        <p class="eyebrow">Selected work</p>
        <h1 id="projects-page-title">More projects</h1>
        <p>Explore the websites and experiments in my portfolio.</p>
      </section>

      <section class="projects-grid projects-page-grid" aria-label="All projects">
        <a class="project-card-link" href="https://kirstenlayters.github.io/Gallery/" target="_blank" rel="noopener noreferrer">
          <div class="project-card">
            <img
              src="/Gallery-website.png"
              alt="Gallery website preview"
              class="project-card-image"
            />
            <div class="project-card-content"><h2>A Gallery website</h2></div>
          </div>
        </a>

        <a class="project-card-link" href="https://kirstenlayters.github.io/bootstrap-/" target="_blank" rel="noopener noreferrer">
          <div class="project-card">
            <img
              src="/Shopping-website.png"
              alt="Demo shopping website preview"
              class="project-card-image"
            />
            <div class="project-card-content"><h2>A demo shopping website</h2></div>
          </div>
        </a>

        <a class="project-card-link" href="https://kirstenlayters.github.io/exercise-3-week-2" target="_blank" rel="noopener noreferrer">
          <div class="project-card">
            <img
              src="/recipes.png"
              alt="Recipes website preview"
              class="project-card-image"
            />
            <div class="project-card-content"><h2>A recipes website</h2></div>
          </div>
        </a>

        <a class="project-card-link" href="https://reprint-kappa.vercel.app/" target="_blank" rel="noopener noreferrer">
          <img
            src="/3D-printing.png"
            alt="3D printer creating a model"
            class="project-card-image"
          />
          <div class="project-card-content"><h2>Reprint - A 3D printing company</h2></div>
        </a>

        <a class="project-card-link" href="https://nuriyahd.github.io/core-project/" target="_blank" rel="noopener noreferrer">
          <img
            src="/modern-tech.png"
            alt="Team collaborating on a modern HR platform"
            class="project-card-image"
          />
          <div class="project-card-content"><h2>Core Project - ModernTech Solutions Automated HR Platform</h2></div>
        </a>

        <a class="project-card-link" href="https://kirstenlayters.github.io/JS-magic-spell-generator/" target="_blank" rel="noopener noreferrer">
          <img
            src="/spell-generator.png"
            alt="Notebook and pen for a spelling tool"
            class="project-card-image"
          />
          <div class="project-card-content"><h2>Spell Generator</h2></div>
        </a>
      </section>
    </main>
  </div>
</template>