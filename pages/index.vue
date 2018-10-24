<template>
  <section class="container">
    <div>
      <logo/>
      <h1 class="title">
        Devisme
      </h1>
      <h2 class="subtitle">
        Generate Your Algorithm
      </h2>
      <p>
         <i>Generate Laravel RestFull API</i> 
         <ul>
            <li><b>Model & DB</b>
              <ul>
                <li>Generate Model</li>
                <li>Generate Migration</li>
                <li>Generate Seeder</li>
              </ul>
            </li>
            
            <li><b>Controller & Resource</b>
              <ul>
                  <li>Generate Controller</li>
                  <li>Generate ResourceCollection</li>
                  <li>Generate Resource</li>
                  <li>Generate Route Api</li>
                  <li>Generate Route Api Documentation</li>
              </ul>
            </li>

            <li><b>View</b>
              <ul>
                  <li>Select View VUE or Blade</li>
                  <li>Design View Base</li>
                  <li>Generate View</li>
              </ul>
            </li>
            
         </ul>
      </p>
      <div class="links">
        <a
          href="https://nuxtjs.org/"
          target="_blank"
          class="button--green">Documentation</a>
        <a
          href="https://github.com/nuxt/nuxt.js"
          target="_blank"
          class="button--grey">GitHub</a>
      </div>
    </div>
  </section>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style>

.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.container p {
  justify-content: left;
  align-items: left;
  text-align: left;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
