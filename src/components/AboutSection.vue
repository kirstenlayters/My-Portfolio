<script setup lang="ts">
import aboutImage from '../assets/IMG_2016.jpg'
</script>

<template>
  <section class="about-card">
    <div id="about-section">
      <h1>About Me</h1>
      <div class="me-container">
        <img
          :src="aboutImage"
          alt="A picture of me"
          class="me"
        />
        <p class="about-me-text">
          My name is Kirsten and I am a trainee at Life Choices Academy, who loves bringing
          ideas into code and existence. I am currently learning about code and how to create
          clean, responsive, and user-friendly websites. Outside of coding, I am probably
          keeping up with my hobbies or creating something new. ♡<br /><br />
          I gained a passion for coding when I discovered how a few lines of code could bring
          an idea to life. What started as curiosity slowly became something I can actually
          enjoy. I love the process of learning new technologies, solving problems, and turning
          creative ideas into functional projects. In the future, I hope to contribute to
          projects that make a difference, as well as empower others to pursue their goals and
          passion while continuing to grow as a developer. ♡
        </p>
      </div>
    </div>
  </section>
</template>
