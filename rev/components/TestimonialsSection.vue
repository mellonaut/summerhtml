<template>
<section class="testimonials-section">
  <h2 class="testimonials-title" data-aos="fade-up">What Our Clients Say</h2>
  <div class="testimonials-container" data-aos="fade-up">
    <div class="testimonial-item">
      <p class="testimonial-text">
        Revolutionary Publishing provided us with invaluable insights into the construction industry. Their publications have significantly enhanced our understanding and decision-making abilities. Highly recommended!
      </p>
      <p class="testimonial-author">- Martin Palmer, Project Manager at StoneBridge Constructions</p>
    </div>
    <div class="testimonial-item">
      <p class="testimonial-text">
        Their service is excellent, and the quality of their publications is unmatched. Our team is more informed and our projects have greatly benefited. Thanks, Revolutionary Publishing!
      </p>
      <p class="testimonial-author">- Lisa Montgomery, Senior Architect at DesignHaus</p>
    </div>
    <div class="testimonial-item">
      <p class="testimonial-text">
        Revolutionary Publishing's resources have been a game changer. Our understanding of the market trends has improved dramatically. Definitely a must for industry professionals.
      </p>
      <p class="testimonial-author">- Aaron Patel, Real Estate Developer at Apex Realty</p>
    </div>
    <div class="testimonial-item">
      <p class="testimonial-text">
        The quality of content provided by Revolutionary Publishing has significantly boosted our team's knowledge. Our decision making is now data-driven, thanks to their timely market analyses.
      </p>
      <p class="testimonial-author">- Rachel Adams, COO of Metro Infrastructure</p>
    </div>
  </div>
</section>
</template>

<script>
export default {}
</script>

<style scoped>
.testimonials-section {
  background-color: var(--background);
  padding: 2em 0;
  text-align: center;
}

.testimonials-title {
  color: var(--primary-light);
  font-size: 2em;
  margin-bottom: 1em;
}

.testimonials-container {
  display: grid;
  gap: 2em;
  justify-items: center;
  width: 90%;
  max-width: 800px;
  margin: 0 auto;
}

.testimonial-item {
  background-image: linear-gradient(
    to right,
    var(--primary-light),
    var(--primary)
  );
  color: var(--background);
  padding: 2em;
  border-radius: 1em;
  max-width: 600px;
}

.testimonial-text {
  font-size: 1.2em;
  line-height: 1.6em;
  margin-bottom: 1em;
}

.testimonial-text::before {
  content: '“';
  color: var(--background);
  font-size: 2em;
}

.testimonial-text::after {
  content: '”';
  color: var(--background);
  font-size: 2em;
}

.testimonial-author {
  font-size: 1em;
  font-style: italic;
}

@media (min-width: 768px) {
  .testimonials-container {
    grid-template-columns: repeat(2, 1fr);
    width: 70%;
  }
}
</style>
