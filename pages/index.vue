<template>
  <div class="home-container">
    <div class="u-full-width">
      <h1 class="site-title">
          <!-- Define Custom Site title or completely change the page -->
          Quality<span class="txt-color"> needs </span>diligence
      </h1>
      <h2>33</h2><p>
SQA Experts      </p> are online.
      <a class="no-highlighter" href="https://sqa.expert" target="_blank">
        <button class="button-primary">
          Connect with Industry Experts!
        </button>
      </a>

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

