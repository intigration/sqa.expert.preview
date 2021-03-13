<template>
  <footer>
    <div class="container-fluid">
        <div class="row middle-xs">
            <div class="col-xs-4 center-xs middle-xs">
              <div class="box">
                <!-- Update your Site -->
                <span class="copyright-text">&#169; SQA Expert</span>
              </div>
            </div>
            <div class="col-xs-4 center-xs middle-xs">
              <div class="box">
                <span class="footer-link">
                  <!-- Update your Git Profile Link -->
                  <a href="https://github.com/intigration/expert" aria-label="Github" target="_blank">
                    <img class="icon-filter" style="color:#fff;" height="24" width="24" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/github.svg" alt="Github"/>
                  </a>
                </span>
              </div>
            </div>
            <!-- Links to pages -->
            <div class="col-xs-4 center-xs middle-xs">
              <div class="box">
                <span class="footer-link"><nuxt-link to="/about">consult</nuxt-link></span>&nbsp;&nbsp;
                <span class="footer-link"><nuxt-link to="/contact">connect</nuxt-link></span>
              </div>
            </div>
        </div>
    </div>
  </footer>
</template>