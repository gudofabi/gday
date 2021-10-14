<template>
  <div class="home-container">
    <!-- BANNER -->
    <div class="banner-container">
      <div class="banner-caption-container">
        <img src="../assets/img/supima-logo-white.png" alt="Supima Logo">
        <div class="caption">
          <h5 class="pb-3">EXPERIENCE SUPIMA SHEETS AT LAS VEGAS MARKET</h5>
          <p class="text-left">Supima Cotton sheets were a big hit at this year's Vegas Market. This 100 percent American-grown extra-long staple cotton is a noticeable upgrade with a premium, luxurious feel that customers love. We also introduced our meticulously finished headboard line and expanded shoulder pillow offering.</p>
          <a href="">View Showroom Recap &gt;</a>
        </div>
      </div>
      <div class="up-coming-shows">
        <h5>Miss Us in Vegas? <a href="">Other Upcoming Shows &gt;</a></h5>
      </div>
    </div>
    <!-- FEATURE -->
    <div class="feature-section">
      <!-- FEATURED -->
      <div class="featured-product-container">
        <div class="container">
          <div class="row">
            <div class="col-xl-4 col-lg-4 col-md-6 col-sm-6 col-xs-12">
              <div class="content">
                <h3>PREMIUM COTTON, LUXURIOUS SHEETS</h3>
                <h4>100% AMERICAN-GROWN SUPIMA COTTON</h4>
                <a href="" class="btn btn-black">VIEW PRODUCT</a>
              </div>
            </div>
            <div class="col-xl-8 col-lg-8 col-md-6 col-sm-6 col-xs-12">
            </div>
          </div>
        </div>
      </div>
      <!-- FEATURES -->
      <div class="features-of-product-container">
        <div class="features-cover d-flex">
          <div class="feature">
            <img src="../assets/img/supima-feel.png" alt="Supima Feel">
            <h5 class="title">Luxurious Feel</h5>
            <p class="description text-left">This superior extra-long staple cotton is 100 percent American grown. The fibers are an impressive 35 percent longer than upland cotton and produce smoother, softer yarns. The result is luxurious sateen sheets with an elegant drape.</p>
          </div>
          <div class="feature">
            <div class="warranty"></div>
            <img src="../assets/img/supima-head.png" alt="Supima Head">
            <h5 class="title">Superior Strength</h5>
            <p class="description text-left">Twice as strong as regular cotton, Supima cotton resists pilling, breaking, and tearing. Backed by our industry-leading 5-year warranty, this resilient fiber lasts longer than regular cotton and keeps its brilliance through years of washing.</p>
          </div>
          <div class="feature">
            <img src="../assets/img/supima-color.png" alt="Supima Color">
            <h5 class="title">Beautiful Color</h5>
            <p class="description text-left">Supima cotton is finely woven and mercerized to create fabric that is softer and more vibrantly colored. Enjoy our elegant color palette of White, Smoke, Flax, and Charcoal for truly luxurious sheeting that customers covet.</p>
          </div>
          <div class="feature">
            <img src="../assets/img/supima-certified-seal.png" alt="Certified Seal">
            <h5 class="title">Protected Fiber</h5>
            <p class="description text-left">Supima &reg; is the trademark used to promoto American-grown, extra-long staple cotton. To bear the Supima trademark, products must be sourced through a licensed supply chain. This process protects buyers from false advertising.</p>
          </div>
        </div>
        <div class="learn-more-container text-center">
          <a href="">Learn More About Supima &gt;</a>
        </div>
        <div class="video-container">
          <div class="video">
            <img class="thumbnail" src="../assets/img/video-thumbnail.jpg" alt="Video Thumbnail">
            <a class="redirect-button" @click="func_handleClick">
              <img src="../assets/img/play-button.png" alt="Play Button">
            </a>
            <!-- Modal -->
              <VideoModal 
                :video-source="`https://player.vimeo.com/video/25883895?autoplay=1&amp;modestbranding=1&amp;showinfo=0`"
                :show-modal="data_modalShow"
                @close="func_closeModal"
              />
          </div>
        </div>
      </div>
    </div>
    <!-- PILLOW -->
    <div class="shoulder-pillow-container d-flex">
      <div class="pillow-title-container">
        <h4 class="text-uppercase">We've Expanded The Z&trade; <br>Shoulder Pillow Line</h4>
        <p class="text-left mb-5">Building on the success of our unique shoulder design, side sleepers can choose from a variety of Dough &reg; pillows to meet their needs and preferences. Our vibrant colors, refreshing fragrances, and beautiful packaging create a very attractive display you won't want to miss.</p>
      </div>
      <div class="desktop-pillows">
        <img src="../assets/img/expanded-z-line-all-together.png" alt="pillows">
        <ul class="pillows-label d-flex">
          <li>
            <h6>Gel Dough<span>&reg;</span> + Z<span>&trade;</span> Gel</h6>
            <a href="">View &gt;</a>
          </li>
          <li>
            <h6>Zoned Gel Dough<span>&reg;</span></h6>
            <a href="">View &gt;</a>
          </li>
          <li>
            <h6>Bamboo Charcoal</h6>
            <a href="">View &gt;</a>
          </li>
          <li>
            <h6>Lavender</h6>
            <a href="">View &gt;</a>
          </li>
          <li>
            <h6>Chamomile</h6>
            <a href="">View &gt;</a>
          </li>
          <li>
            <h6>Peppermint</h6>
            <a href="">View &gt;</a>
          </li>
        </ul>
      </div>
      <div class="mobile-pillows">
        <div class="pillows">
          <img src="../assets/img/divided-z-line.png" alt="Upper Pillows">
          <ul class="pillows-label d-flex">
            <li>
              <h6>Lavender</h6>
              <a href="">View &gt;</a>
            </li>
            <li>
              <h6>Chamomile</h6>
              <a href="">View &gt;</a>
            </li>
            <li>
              <h6>Peppermint</h6>
              <a href="">View &gt;</a>
            </li>
          </ul>
        </div>
        <div class="pillows">
          <img src="../assets/img/divided-z-line-2.png" alt="Upper Pillows">
          <ul class="pillows-label d-flex">
            <li>
              <h6>Gel Dough<span>&reg;</span> + Z<span>&trade;</span> Gel</h6>
              <a href="">View &gt;</a>
            </li>
            <li>
              <h6>Zoned Gel Dough<span>&reg;</span></h6>
              <a href="">View &gt;</a>
            </li>
            <li>
              <h6>Bamboo Charcoal</h6>
              <a href="">View &gt;</a>
            </li>
          </ul>
        </div>
      </div>
    </div>
    <!-- GALLERY -->
    <div class="gallery-container d-flex flex-column align-items-center bg-light-grey">
      <div class="gallery-cover d-flex">
        <div class="thumbnail-cover d-flex flex-column-reverse">
          <div class="img-container">
            <img src="../assets/img/headboard.jpg" class="shadow" alt="">
          </div>
          <div class="info text-right">
            <h6>A touch of elegance:</h6>
            <p>New Structures&trade; Headboards</p>
          </div>
        </div>
        <div class="thumbnail-cover d-flex flex-column">
          <div class="img-container shadow">
            <img src="../assets/img/showroom.jpg" class="shadow"  alt="">
          </div>
        </div>
        <div class="thumbnail-cover d-flex flex-column">
          <div class="img-container shadow">
            <img src="../assets/img/hamburger.jpg" class="shadow"  alt="">
          </div>
          <div class="info">
            <h6 class="text-white">A sentional experience:</h6>
            <p class="text-light-grey">Chef-Prepared Groumet Food &amp; Giveaways</p>
          </div>
        </div>
      </div>
      <div class="thankyou-container w-100 text-center">
        <h2 class="text-white mb-3">Thank you</h2>
        <h6 class="text-light-grey mb-4">For another great market</h6>
        <a href="" class="font-weight-normal">View Showroom Recap &gt;</a>
      </div>
      <div class="appointment-container w-100 text-center">
        <h2 class="text-white mb-4">Appointment Available</h2>
        <p class="text-light-grey mb-4 sans-serif">For an appointment, contact us at: <br>sales@maloufsleep.com | 800.517.7179</p>
        <h6 class="text-white">Las Vegas Market <br>July 30 - August 3, 2017 <br>Space C1540</h6>
      </div>
    </div>
  </div>
</template>

<script>
import VideoModal from  '@/components/VideoModal.vue';
export default {
  name: 'Home',
  components: {
    VideoModal
  },
  data () {
    return {
      data_videoSource: '',
      data_modalShow: false
    }
  },
  methods: {
    func_handleClick() {
      this.data_modalShow = true;
    },
    func_closeModal(value) {
      this.data_modalShow = value;
    }
  }
}
</script>
