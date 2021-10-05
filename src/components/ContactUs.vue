<template >
  <section class="bg-light p-5 text-center text-light p-lg-0">
    <div class="container">
      <div class="d-sm-flex p-2 align-items-center justify-content-between">
        <img
          src="https://www.pikpng.com/pngl/m/12-120187_call-center-girl-png-indian-call-centre-girl.png"
          class="img-fluid w-50 d-none d-sm-block ml-5"
          alt="Call Center Girl Png - Indian Call Centre Girl Clipart@pikpng.com"
          style="margin-left: 5rem; background-color: transparent"
        />
        <div class="">
          <h1 class="text-success" style="">
            Contact <span class="text-warning"> Us</span>
          </h1>
          <p
            class="lead my-4 text-dark"
            style="
              font-size: small;
              opacity: 0.6;
              font-weight: bold;
              padding-left: 2rem;
              margin-right: 1rem;
            "
          >
            Do you want to make an enquiry, a complaints, or you just want to
            know more about us? then you are on the right page. Send us a
            message right here and contact us on any channel listed below.
          </p>
        </div>
      </div>
    </div>
  </section>

  <Address />
  <!-- h elp and support-->
  <Help />

  <Investment />
  <Footer />
</template>

<script>
import Investment from "./Investment.vue";
import Footer from "./Footer.vue";
import Address from "./Address.vue";
import Help from "./Help&Support.vue";

export default {
  name: "Contact",
  components: {
    Investment,
    Footer,
    Address,
    Help,
  },
};
</script>

<style scoped>
.location {
  border-radius: 5rem !important;
}
</style>


