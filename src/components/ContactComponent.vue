<template>
  <section class="head pb-5" id="Contact">
      <div class="container py-5">
        <div class="card">
          <div class="card-bodyContact">
            <h1 class="font-weight-light text-center py-5">Contact Me</h1>
            <div class="row">
              <div class="col-lg-6 col-md-12 col-sm-12 col-12">
                <div class="row pt-3">
                  <div class="col-lg-1 offset-1 col-md-2 col-sm-2 col-2">
                    <i class="fa-solid fa-location-dot"></i>
                  </div>
                  <div class="col-lg-10 col-md-9 col-sm-9 col-9">
                    <h5 class="font-weight-light"><b>Address</b></h5>
                    <p>A28 Shefiled Rd.<br>
                      Browns Farm<br>
                      Philippi<br>
                      7785</p>
                  </div>
                </div>
                <div class="row pt-3">
                  <div class="col-lg-1 offset-1 col-md-2 col-sm-2 col-2">
                    <i class="fa-solid fa-phone"></i>

                  </div>
                  <div class="col-lg-10 col-md-9 col-sm-9 col-9">
                    <h5 class="font-weigh-light"><b>Give me a call</b></h5>
                    <p>+27 68 522 8188</p>
                  </div>
                </div>
                <div class="row pt-3">
                  <div class="col-lg-1 offset-1 col-md-2 col-sm-2 col-2">
                    <i class="fa-solid fa-paper-plane"></i>

                  </div>
                  <div class="col-lg-10 col-md-9 col-sm-9 col-9">
                    <h5 class="font-weight-light"><b>Email Me</b></h5>
                    <p>17MkhuseliMkeyiya@gmail.com</p>
                  </div>
                </div>
              </div>
              <div class="col-lg-6 col-md-12 col-sm-12 col-12">
                <form action="https://formspree.io/f/mqkjgnln" method="post">

                  <div class="form-row">
                    <div class="form-group col-lg-6 col-md-12 col-sm-12 col-12">
                      <label>First Name</label>
                      <input type="text" class="form-control" placeholder="First Name" name="firstName">
                    </div>
                    <div class="form-group col-lg-6 col-md-12 col-sm-12 col-12">
                      <label>Last Name</label>
                      <input type="text" class="form-control" placeholder="Last Name" name="lastName">
                    </div>
                  </div>
                  <label>Email</label>
                  <input type="email" placeholder="someone@gmail.com" class="form-control" name="EmailAddres">
                  <label>Your Message</label>
                  <textarea class="form-control mb-3" id="" placeholder="Enter your message" cols="30"
                    rows="10" name="Message"></textarea>
                  <button class="btn">Send Message</button>
                </form>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
</template>
<script>
export default {

}
</script>
