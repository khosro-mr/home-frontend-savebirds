<template>
  <main class="container py-5">
    <div class="row align-items-center">
      <!-- Explanation Section - Left side on desktop, top on mobile -->
      <section class="col-lg-6 mb-4 mb-lg-0">
        <h1 class="display-4 fw-bold mb-3">SaveBirds</h1>
        
        <div class="mb-4">
          <p class="lead">
            SaveBirds is a comprehensive tool designed for analyzing North American Breeding Bird Survey data, providing valuable insights into bird population trends.
          </p>
          <p>
            Our application helps conservation efforts by making complex bird survey data accessible and actionable. By visualizing population changes over time, SaveBirds enables researchers, conservationists, and bird enthusiasts to identify at-risk species and develop targeted protection strategies.
          </p>
          <p>
            With SaveBirds, you can perform various analyses, including population trend visualization, species comparison, and habitat correlation studies - all through an intuitive and user-friendly interface.
          </p>
        </div>

        <button 
          class="btn btn-success btn-lg px-4" 
          @click="navigateToMetrics"
        >
          Get Started
        </button>
      </section>

      <!-- Bird Image Section - Right side on desktop, bottom on mobile -->
      <section class="col-lg-6">
        <img 
          src="../assets/images/eagle.jpg" 
          alt="Bald Eagle standing on wood" 
          class="img-fluid rounded shadow-sm"
        />
      </section>
    </div>
  </main>
</template>

<script>
export default {
  name: 'HomeView',
  methods: {
    navigateToMetrics() {
      // Will be implemented when router is set up
      // this.$router.push('/metrics')
      console.log('Navigate to Metrics page')
    }
  }
}
</script>

<style scoped>
/* Most styling is handled by Bootstrap classes */
/* Additional custom styles if needed */
</style> 