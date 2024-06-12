<template>
  <div class="services-container">
    <h2>Our Services</h2>
    <div class="cards">
      <div class="card">
        <img src="./assets/IWD.svg" alt="Integrated Web Development">
        <h3>Integrated Web Development</h3>
        <p>At our studio, we understand that modern web development requires an integrated approach, and we strive to ensure that every project is not just completed but executed with excellence, utilizing all the capabilities of the modern technology stack.</p>
      </div>
      <div class="card">
        <h3>Automation Scripts</h3>
        <p>At our studio, we offer automation services that can transform any aspect of your business. Our script automation solutions can reduce time spent on routine tasks, minimize errors, and increase overall efficiency.</p>
      </div>
      <div class="card">
        <h3>Custom Development</h3>
        <p>If you haven't found a suitable option among the services we offer, don't worry! We're here to help you create a customized web application that fully meets your unique requirements and expectations. Just let us know.</p>
      </div>
      <div class="card">
        <h3>SaaS Solutions</h3>
        <p>Our team offers innovative and efficient SaaS solutions to optimize your business and achieve your goals with maximum productivity. These cloud-based solutions are delivered to you as a flexible and scalable subscription, allowing you to utilize the applications without worrying about installation, upgrades, and maintenance.</p>
      </div>
    </div>
  </div>
</template>

<script>

</script>

<style scoped>
.services-container {
  text-align: center;
  padding: 20px;
}

.cards {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 20px;
  margin-top: 20px;
}

.card {
  background: linear-gradient(135deg, #632ADC 0%, #2B8DE6 60%, #41E0FA 100%);
  border-radius: 8px;
  padding: 20px;
  width: 300px;
  height: 600px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s;
  color: white;
}

.card:hover {
  transform: translateY(-10px);
}

.card h3 {
  margin: 0 0 10px 0;
  font-size: 18px;
}

.card p {
  text-align: left;
  margin: 0;
  font-size: 14px;
  color: #e0e0e0;
}
</style>