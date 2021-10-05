
 <template>
  <div class="cardo">
    <nav class="navbar navbar-expand-lg navbar-light bg-light pt-4">
      <div class="container-fluid" style="padding-top: 1rem">
        <a class="navbar-brand" href="#">RELSIFY</a>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav ms-auto mb-2 mb-lg-0" p-3 px-3>
            <li class="nav-item">
              <a
                class="nav-link active"
                aria-current="page"
                href="#"
                style="color: green"
              >
                About Finacle</a
              >
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Explore market place</a>
            </li>

            <li class="nav-item">
              <a class="nav-link" href="#">Tokenize your property</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Login</a>
            </li>
            <li class="nav-item">
              <a
                class="nav-link"
                href="#"
                style="color: #000000; font-size: large"
                >Sign up</a
              >
            </li>
          </ul>
        </div>
      </div>
    </nav>
   <Contact/>
  </div>


  <!-- contact component -->
 
 
</template>

<script>

import Contact from "./ContactUs.vue"


export default {
  name: "Navbar",
  components: {
    Contact,
    
  },
};
</script>
 

<style scoped>
a.nav-link {
  color: #778899;
  font-size: small;
  font-weight: bold;
}
nav {
  background-color: transparent !important;
  border: none !important;
  outline: none !important;
}
.navbar-brand {
  color: #00806b!important;
  font-weight: bold;
  padding-left: 2rem;
}
.cardo {
  width: 90%;
}
li {
  padding-left: 1rem;
  padding-right: 1rem;
}
a:hover {
  border: 1px solid  rgb(217, 255, 0);
}
</style>