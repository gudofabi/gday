<template>
  <div class="gday-contact">
    <div class="container">
      
      <ul class="breadcrumb">
          <li><a href="#">Contact Us</a></li>
          <li class="active">Details</li>
      </ul>

      <div class="row">
        <div class="col-12 col-md-6">
            <div class="contact-details">
              <h1>Contact Us</h1>
              <p class="sub-title">Our Contact Details</p>

              <div class="contacts">
                <div class="detail">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z" />
                    </svg>
                    <span>1300 061 811</span>
                </div>
                <div class="detail">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 21V5a2 2 0 00-2-2H7a2 2 0 00-2 2v16m14 0h2m-2 0h-5m-9 0H3m2 0h5M9 7h1m-1 4h1m4-4h1m-1 4h1m-5 10v-5a1 1 0 011-1h2a1 1 0 011 1v5m-4 0h4" />
                    </svg>
                    <span>Level 7, 60 Light Square<br> Adelaide, South Australia 5000 Australia</span>
                </div>
              </div>
            </div>
        </div>
        <div class="col-12 col-md-6">
          <div class="form-cover">

            <div class="row">
              <div class="form-group col-6">
                <label for="">First Name</label>
                <input type="text" class="form-control">
              </div>
              <div class="form-group col-6">
                <label for="">Last Name</label>
                <input type="text" class="form-control">
              </div>
            </div>

            <div class="row">
              <div class="form-group col-6">
                <label for="">Email</label>
                <input type="text" class="form-control">
              </div>
              <div class="form-group col-6">
                <label for="">Phone</label>
                <input type="text" class="form-control">
              </div>
            </div>

            <div class="form-group">
              <label for="">Message</label>
              <textarea name="" id="" cols="30" rows="7" class="form-control"></textarea>
            </div>

            <button class="btn btn-primary mt-4">Send Enquiry</button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Home',
}
</script>
