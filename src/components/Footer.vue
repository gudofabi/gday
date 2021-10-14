<template>
  <!-- FOOTER -->
    <footer class="malouf-footer d-flex flex-column bg-light-grey">
      <!-- Upper -->
      <div class="upper-footer d-flex d-flex-wrap justify-content-between">
        <div class="footer-container first-con d-flex flex-column justify-content-between">
          <div class="social-media-cover">
            <h6 class="title mb-4">Follow Us</h6>
            <ul class="social-media d-flex justify-content-between">
              <li>
                <a href="">
                  <font-awesome-icon size="lg" :icon="['fab', 'facebook-f']" />
                </a>
              </li>
              <li>
                <a href="">
                  <font-awesome-icon size="lg" :icon="['fab', 'instagram']" />
                </a>
              </li>
              <li>
                <a href="">
                  <font-awesome-icon size="lg" :icon="['fab', 'pinterest']" />
                </a>
              </li>
              <li>
                <a href="">
                  <font-awesome-icon size="lg" :icon="['fab', 'twitter']" />
                </a>
              </li>
            </ul>
          </div>
          <div class="contact-cover">
            <h6 class="title mt-5 mb-3">Contact Us</h6>
            <ul class="contact-list">
              <li><span>info@maloufsleep.com</span></li>
              <li><span>(800) 517-719</span></li>
            </ul>
          </div>
        </div>
        <div class="footer-container second-con">
          <ul class="pillows-links">
            <li>
              <a>Z pillows</a>
            </li>
            <li>
              <a>Wooven Linens</a>
            </li>
            <li>
              <a>Sleep Tite Protectors</a>
            </li>
            <li>
              <a>Isolus Toppers</a>
            </li>
            <li>
              <a>Structure Frames</a>
            </li>
          </ul>
        </div>
        <div class="footer-container third-con">
          <ul class="helpful-links">
            <li>
              <a>Retailer Login</a>
            </li>
            <li>
              <a>Product Information</a>
            </li>
            <li>
              <a>About Us</a>
            </li>
            <li>
              <a>Showrooms</a>
            </li>
            <li>
              <a>Giving Back</a>
            </li>
            <li>
              <a>Media</a>
            </li>
          </ul>
        </div>
        <div class="footer-container fourth-con">
          <h6 class="title">Latest news</h6>
          <div class="latest-news-list">
            <div class="post-cover">
              <img src="../assets/img/event-1.jpg" alt="Event 1">
              <div class="info">
                <p class="sans-serif font-weight-bold">Malouf Celebrates Growth with New Corporate Headquarters</p>
                <a>Read more &gt;</a>
              </div>
            </div>
            <div class="post-cover">
              <img src="../assets/img/event-2.jpg" alt="Event 2">
              <div class="info">
                <p class="sans-serif font-weight-bold">Malouf Release Ground-breaking Biodegradable Mattress Infused with Seeds</p>
                <a>Read more &gt;</a>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- Bottom -->
      <div class="bottom-footer">
        <p>2016 Malouf. All rights reserved. Privacy policy | Terms of Service</p>
      </div>
    </footer>
</template>

<script>
export default {
    name: 'Footer'
}
</script>

<style>

</style>