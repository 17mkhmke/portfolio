<template>
  <section class="contact" id="contact">
    <div class="container">
      <div class="card">
        <div class="card-body">
          <h1 class="title">Contact</h1>
          <div class="row">
            <div class="col-md-6">
              <div class="address">
                <h3>Address</h3>
                <p>Browns Farm</p>
                <p>Philippi</p>
                <p>7785</p>
              </div>
              <div class="phone">
                <h3>Phone</h3>
                <p>+27 68 522 8188</p>
              </div>
              <div class="email">
                <h3>Email</h3>
                <p>17MkhuseliMkeyiya@gmail.com</p>
              </div>
            </div>
            <div class="col-md-6">
              <form action="https://formspree.io/f/mqkjgnln" method="post">
                <div class="form-group">
                  <input type="text" class="form-control" placeholder="First Name" name="firstName" required>
                </div>
                <div class="form-group">
                  <input type="text" class="form-control" placeholder="Last Name" name="lastName" required>
                </div>
                <div class="form-group">
                  <input type="email" class="form-control" placeholder="Email Address" name="EmailAddres" required>
                </div>
                <div class="form-group">
                  <textarea class="form-control" placeholder="Your Message" name="Message" required></textarea>
                </div>
                <button type="submit" class="btn btn-primary">Send Message</button>
              </form>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Mouse+Memoirs&family=Quicksand:wght@500&display=swap');
.contact {
  background-color: #FDEEE3;
  color: #08233B;
  font-family: 'Mouse Memoirs', sans-serif;
  padding: 5rem 0;
}

.title {
  font-weight: 400;
  font-size: 70px;
  margin-bottom: 3rem;
  text-align: center;
}

.card {
  background-color: #fff ;
  box-shadow: 0 0.5rem 1.5rem rgba(0, 0, 0, 0.1);
  padding: 2rem;
  border-radius: 1rem;
}

.address h3, .phone h3, .email h3 {
  font-size: 40px;
  font-weight: 500;
  margin-bottom: 1rem;
}

.address p, .phone p, .email p {
  margin-bottom: 1rem;
  font-size: 20px;
}

.form-group {
  margin-bottom: 2rem;
}

input.form-control, textarea.form-control {
  border: none;
  border-radius: 0;
  border-bottom: 2px solid #ccc;
  box-shadow: none;
  padding: 1rem 0;
}

input.form-control:focus, textarea.form-control:focus {
  border-color: #08233B;
  box-shadow: none;
}

.btn-primary {
  background-color: #08233B;
  /* border-color: #08233; */

}

.btn-primary:hover{
  color:#FA8072;
}
</style>
