<template>
  <section class="about-section">
    <div class="about-container" data-aos="fade-up">
      <h2 class="about-title">About Revolutionary Publishing</h2>
      <div class="about-details">
        <div class="detail-item">
          <i class="fas fa-globe-americas detail-icon"></i>
          <p>
            We are a specialized publishing company, focusing on the construction and real estate sectors.
          </p>
        </div>
        <div class="detail-item">
          <i class="fas fa-building detail-icon"></i>
          <p>
            Our team of experts collaboratively produce industry-leading publications to keep professionals informed and ahead of the market trends.
          </p>
        </div>
      </div>
    </div>
    <div class="service-container" data-aos="fade-up">
      <h2 class="service-title">Our Services</h2>
      <div class="service-details">
        <div class="detail-item">
          <i class="fas fa-book detail-icon"></i>
          <p>
            Our comprehensive publishing services deliver insightful content and up-to-date market analyses, providing invaluable resources for industry professionals.
          </p>
        </div>
        <div class="detail-item">
          <i class="fas fa-cogs detail-icon"></i>
          <p>
            We handle everything from content creation to distribution, allowing professionals to focus on their projects while staying informed.
          </p>
        </div>
      </div>
    </div>
    <div class="cta-container" data-aos="fade-up">
      <a
        class="cta-button"
        href="https://api.whatsapp.com/send?phone=yourphonenumber"
        target="_blank"
      >
        <i class="fas fa-rocket"></i> Learn More
      </a>
    </div>
  </section>

</template>

<script>
export default {}
</script>

<style>
.about-section {
  background-color: var(--background);
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  padding: 2em 0;
}

.about-container,
.service-container {
  width: 90%;
  max-width: 800px;
  margin-bottom: 2em !important;
}

.about-title,
.service-title {
  color:  var(--primary);
  font-size: 2em;
  text-align: center;
  margin-bottom: 1em;
}

.about-details,
.service-details {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 2em;
}

.detail-item {
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
}

.detail-icon {
  color: var(--primary);
  font-size: 2em;
  margin-bottom: 0.5em;
}

.cta-container {
  display: flex;
  justify-content: center;
  margin-top: 1.5em;
}

.cta-button {
  background-color: var(--accent);
  border: none;
  border-radius: 2em;
  color: var(--background);
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 1.2em;
  padding: 1em 2em;
  transition: background-color 0.3s ease;
  text-decoration: none;
}

.cta-button i {
  margin-right: 0.5em;
}

.cta-button:hover {
  background-color: var(--primary-light);
}

.cta-button:active {
  background-color: var(--primary-dark);
}

@media (min-width: 768px) {
  .about-container,
  .service-container {
    width: 70%;
  }
}
</style>
