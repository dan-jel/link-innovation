<template>
  <section class="probootstrap-section">
    <div class="container">
      <div class="row mb-5">
        <div class="col-md-12">
          <form action="#" method="post" class="probootstrap-form mb-5">
            <div class="row">
              <div class="col-md-6">
                <div class="form-group">
                  <label for="fname">First Name</label>
                  <input
                    type="text"
                    class="form-control"
                    id="fname"
                    name="fname"
                  />
                </div>
              </div>
              <div class="col-md-6">
                <div class="form-group">
                  <label for="lname">Last Name</label>
                  <input
                    type="text"
                    class="form-control"
                    id="lname"
                    name="lname"
                  />
                </div>
              </div>
            </div>
            <div class="form-group">
              <label for="email">Email</label>
              <input
                type="email"
                class="form-control"
                id="email"
                name="email"
              />
            </div>
            <div class="form-group mb-4">
              <label for="message">Message</label>
              <textarea
                cols="30"
                rows="10"
                class="form-control"
                id="message"
                name="message"
              ></textarea>
            </div>
            <div class="form-group">
              <input
                type="submit"
                class="btn btn-primary"
                id="submit"
                name="submit"
                value="Send Message"
              />
            </div>
          </form>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "ContactForm",
};
</script>
