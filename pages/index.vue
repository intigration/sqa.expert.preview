<template>
  <div class="home-container">
    <div class="u-full-width">
      <h1 class="site-title">
          <!-- Define Custom Site title or completely change the page -->
          Quality<span class="txt-color"> needs </span>diligence
      </h1>
        <a class="no-highlighter" href="https://sqa.expert" target="_blank">
        <button class="button-primary">
          Find Industry Experts!
        </button>
      </a>
      <h3><p> 33 Experts are online.</p></h3>
    

    </div>
    <!-- This is used to load the netlify identity widget so you can use Netlify CMS -->
  <!--  <script async src="https://identity.netlify.com/v1/netlify-identity-widget.js"></script> -->
  </div>
</template>

<script>
export default {
  // Define SEO Variables / Site Title, etc.
  head() {
    return {
      title: this.siteName || 'SQA Expert',
      meta: [
      { hid: 'description',
      name: 'description',
      content: 'Experts are online!' }
      ]
    };
  },
  async asyncData({ env }) {
    const siteName = env.SITE_NAME
    return {
      siteName
    }
  }
}
</script>

