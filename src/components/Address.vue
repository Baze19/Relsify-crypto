<template>
  <!--  -->
  <section class="p-5 p-lg-0" style="margin-top: -4rem">
    <div class="container">
      <div class="row">
        <div class="col-md-1"></div>
        <div
          class="
            col-md-5
            mt-5
            p-3
            d-flex
            flex-column
            justify-content-sm-center
            flex-wrap
          "
        >
          <div
            class="
              d-flex
              justify-content-center
              align-items-center
              p-2
              text-center
              mb-4
              text-light
            "
            style="
              border-radius: 2rem;
              border-left: 9px solid #ffd700;
              opacity: 0.8;
              border-left-radius: 1px;
              background-color: #00806b;
            "
          >
            <span>
              <i
                class="bi bi-geo"
                style="font-size: 5rem; margin-right: 2rem; margin-left: 2rem"
              ></i
            ></span>
            <div class="adress">
              <span> No 3 our address location </span>
              <span>Lagos Nigeria</span>
            </div>
          </div>

          <div
            class="
              d-flex
              justify-content-center
              align-items-center
              p-2
              text-center
              mb-4
            "
            style="border-left: 9px solid #00806b"
          >
            <span>
              <i
                class="bi bi-telephone-plus"
                style="font-size: 5rem; margin-right: 2rem; color: #00806b"
              ></i
            ></span>
            <div class="adress">
              <span>+234 8168543919</span>
              <span>+234 6778855444</span>
            </div>
          </div>
          <div
            class="
              d-flex
              justify-content-center
              align-items-center
              p-2
              text-center
              mb-4
            "
            style="border-left: 9px solid #00806b"
          >
            <span>
              <i
                class="bi bi-envelope"
                style="font-size: 5rem; margin-right: 2rem; color: #00806b"
              ></i>
            </span>
            <div class="adress">
              <span>Relsify@ gmail.com</span>
              <span>info@relsify@gmail.com</span>
            </div>
          </div>
        </div>
        <div class="col-md-1"></div>
        <div
          class="col-md-5 p-2"
          style="border-radius: 1rem; background-color: #00806b; opacity: 0.8"
        >
          <div class="container">
            <h1
              class="text-light text-center mt-3 mb-3"
              style="font-weight: bold"
            >
              Write <span class="text-warning"> Us</span>
            </h1>
            <div class="row mt-2">
              <div
                class="col-sm-5 d-flex"
                style="
                  border: 1px solid black;
                  background-color: white;
                  border-radius: 1rem;
                "
              >
                <span style="padding-top: 0.4rem; opacity: 0.6"
                  ><i class="bi bi-person-circle"></i
                ></span>
                <input
                  type="text"
                  class="form-control"
                  aria-label="Sizing example input"
                  aria-describedby="inputGroup-sizing-default"
                  placeholder="Name"
                />
              </div>
              <div class="col-sm-1"></div>
              <div
                class="col-sm-5 d-flex"
                style="
                  border: 1px solid black;
                  background-color: white;
                  border-radius: 1rem;
                "
              >
                <span style="padding-top: 0.4rem; opacity: 0.6"
                  ><i class="bi bi-person-circle"></i
                ></span>
                <input
                  type="text"
                  class="form-control"
                  aria-label="Sizing example input"
                  aria-describedby="inputGroup-sizing-default"
                  placeholder="Email"
                />
              </div>

              <!-- tetxarea -->
              <div class="mt-5 mb-5">
                <textarea
                  class="form-control"
                  id="exampleFormControlTextarea1"
                  rows="9"
                  placeholder="message"
                  style="border-radius: 2rem"
                ></textarea>
              </div>
              <!-- button -->
              <div class="mt-4 mb-5 text-center">
                <button
                  class="btn btn-warning"
                  type="button"
                  style="
                    width: 100%;
                    padding: 0.9rem;
                    border-radius: 2rem;
                    opacity: 0.8;
                  "
                >
                  Send Message
                </button>
              </div>
            </div>
          </div>
        </div>
        <div class="col-md-1"></div>
      </div>
    </div>
  </section>
</template>




<script>
export default {
  name: "Address",
};
</script>

<style scoped>
.adress {
  font-size: normal;
  line-height: -2rem;
  opacity: 0.8;
  display: flex;
  flex-direction: column;
  padding-right: 1rem;
}
.location {
  border-radius: 5rem !important;
}
</style>