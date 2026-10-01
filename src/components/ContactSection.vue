<template>
  <section class="contact-layout">
    <div class="contact-info-card">
      <h3>Alternative Contact</h3>
      <p>📍 Cape Town, South Africa</p>
      <p>👩‍💻 <a href="https://github.com/kirstenlayters" target="_blank">My GitHub</a></p>
      <p>✉️ <a href="https://www.linkedin.com/in/kirsten-layters-48b434371/" target="_blank">My LinkedIn</a></p>
    </div>

    <div class="contact-card">
      <div id="contact-section">
        <form action="https://formspree.io/f/mvzngjlk" method="POST">
          <h2>Contact form!</h2>
          <div class="form-group">
            <label for="full_name">Full name</label>
            <input type="text" id="full_name" name="full_name" autocomplete="name" required />
          </div>

          <div class="form-group">
            <label for="email">Email</label>
            <input type="email" id="email" name="email" autocomplete="email" required />
          </div>

          <div class="form-group">
            <label for="message">Reason for contact</label>
            <textarea id="message" rows="5" name="message" required></textarea>
          </div>

          <button type="submit" class="submit-button">Submit form</button>
        </form>
      </div>
    </div>
  </section>
</template>
