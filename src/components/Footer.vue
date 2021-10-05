<template >
  <div class="container mt-5 pb-5 bg-light">
    <section class="p-5 mb-1">
      <div class="container">
        <div
          class="d-md-flex justify-content-between p-2"
          style="text-align: justify"
        >
          <div class="col-lg-3">
            <h5>RESIFY</h5>

            <p class="mt-3 mb-3" style="font-size: small; font-weight: bold">
              Lorem ipsum dolor sit amet consectetur adipisicing<br />
              elit. Error cum sit placeat natus doloribus perspiciatis explicabo
              vero velit! Voluptatem voluptate cumque vero nemo eum culpa velit
              totam pariatur ratione aut.
            </p>
          </div>
          <div
            class="
              col-md-1
              resify
              d-flex
              justify-content-center
              align-items-center
            "
          ></div>
          <div class="col-md-2 ml-2">
            <h5>Investor</h5>
            <p class="mt-3 mb-3">Tokenised Properties</p>
            <p style="font-size: small; font-weight: bold">
              Calculated Token Rate
            </p>
          </div>

          <div class="col-md-3">
            <h5>Real Estate Manager</h5>
            <p class="mt-3 mb-3">Start a Real Estate Career</p>
            <p>Property Analysis Tool</p>
            <p>Sell Your Property</p>
            <p>Finance Your Property</p>
          </div>

          <div class="col-md-2">
            <h5>Resources</h5>
            <p class="mt-3 mb-3">Blog</p>
            <p>White Paper</p>
            <p>FAQ</p>
          </div>

          <div class="col-md-2">
            <h5>RELSIFY</h5>
            <p class="mt-3 mb-3">About</p>
            <p>Terms & Condition</p>
            <p>Privacy</p>
          </div>
        </div>
      </div>
    </section>
    <p class="text-center lead">
      Copyright &copy; 2021 Abiodun relsify frontend
    </p>
  </div>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style scoped>
h5 {
  text-align: justify;
  color: #00804f;
  font-weight: bold;
  opacity: 0.6;
}

p {
  font-size: small;
  font-weight: bold;
}
.resify {
  position: relative;
}
.resify::after {
  content: "";
  border: 1px solid gray;
  position: absolute;
  right: 0;
  top: 0;
  width: 0;
  height: 100%;
  margin-right: 1rem;
  bottom: -20%;
  opacity: 0.3;
}
</style>