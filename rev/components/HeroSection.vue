<template>
  <section class="hero-section">
    <div class="content-container" data-aos="fade-up">
      <h1 class="hero-title">The Future of Publishing</h1>
      <p class="hero-subtitle">Architecting New Media Strategies</p>
      <p class="hero-description">
        Leading provider of media and publishing services for the construction industry and commercial real-estate.
      </p>
      <div class="cta-button-container">
        <a
          class="cta-button"
          href="https://api.whatsapp.com/send?phone=212619848735"
          target="_blank"
        >
          <i class="fas fa-rocket"></i> Get Started
        </a>
      </div>
    </div>
    <div class="hero-image-container" data-aos="fade-up">
      <img
        src="@/assets/images/underconstruction.jpg"
        alt="Revolutionary Publishing - Building Dreams"
      />
    </div>
  </section>
</template>

<script>
export default {}
</script>

<style scoped>
.hero-section {
  background: linear-gradient(135deg, var(--primary), var(--secondary));
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  padding: 2em 1em;
  text-size-adjust: 100%;
}

.hero-title {
  color: var(--background);
  font-size: 2em;
  text-align: center;
  text-size-adjust: 100%;
}

.hero-subtitle {
  color: var(--background);
  font-size: 1.5em;
  margin-top: 0.5em;
  text-align: center;
  text-size-adjust: 100%;
}

.hero-description {
  color: var(--background);
  font-size: 1.2em;
  line-height: 1.6em;
  margin-top: 1em;
  text-align: center;
  max-width: 600px; /* To keep the line length comfortable to read */
  text-size-adjust: 100%;
}

.cta-button-container {
  display: flex;
  justify-content: center;
  margin-top: 1.5em;
  text-size-adjust: 100%;
}

.cta-button {
  background-color: var(--background);
  border: none;
  border-radius: 2em;
  color: var(--primary);
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 1.2em;
  padding: 1em 2em;
  text-decoration: none; /* Since it's a link now, not a button */
  transition: all 0.3s ease;
  text-size-adjust: 100%;
}

.cta-button i {
  margin-right: 0.5em;
}

.cta-button:hover {
  background-color: var(--primary-dark);
  color: var(--background);
  transform: scale(1.05); /* Added scale effect on hover */
}

.cta-button:active {
  background-color: var(--primary-dark);
  color: var(--background);
}

.hero-image-container img {
  width: 100%;
  height: auto;
  text-size-adjust: 100%;
}

.content-container {
  margin-bottom: 2em;
  text-size-adjust: 100%;
}

@media (min-width: 768px) {
  .hero-section {
    flex-direction: row;
    justify-content: space-around;
    text-size-adjust: 100%;
  }
  .content-container {
    margin-bottom: 0;
    width: 45%;
    text-size-adjust: 100%;
  }
  .hero-image-container {
    width: 45%;
    text-size-adjust: 100%;
  }
}
</style>
