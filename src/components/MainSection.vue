<template>
  <div class="hello">
    <section id="service">
      <div class="container">
        <h2>Explore Our Services</h2>
        <div class="service_wrapper">
          <div class="row">
            <div class="col-lg-3">
              <div class="service_icon delay-03s animated wow zoomIn">
                <span><img src="../assets/1.jpg" alt="" /> </span>
              </div>
              <div class="service_block">
                <h3 class="animated fadeInUp wow">Home Cleaning</h3>
                <p class="animated fadeInDown wow">
                  Need help clearing the trash, clearning windows, sofar/capet
                  vacuuming or kitchen cleaning services ? We offer a broad
                  range of these services and more. Including bathroom cleaning,
                  mopping/disinfection of floors and balcony areas and complete
                  dusting services
                </p>
              </div>
            </div>
            <div class="col-lg-3">
              <div class="service_icon icon2 delay-03s animated wow zoomIn">
                <span
                  ><img
                    src="../assets/lawnmower-384589_1920.jpg"
                    alt=""
                    class="img-fluid"
                  />
                </span>
              </div>
              <div class="service_block">
                <h3 class="animated fadeInUp wow">Grass/Cutting Lawn</h3>
                <p class="animated fadeInDown wow">
                  We offer a wide range of lawn maintenance services. From
                  Cutting, pruning and other gardening services
                </p>
              </div>
            </div>
            <div class="col-lg-3">
              <div class="service_icon icon3 delay-03s animated wow zoomIn">
                <span
                  ><img src="../assets/laundry-413688_1920.jpg" alt="" />
                </span>
              </div>
              <div class="service_block">
                <h3 class="animated fadeInUp wow">
                  Laundering and dry cleaning
                </h3>
                <p class="animated fadeInDown wow">
                  We provide professional laundry service covering a wide range
                  of materials and fabrics. Shirts, Pants, Towels, BedSheets,
                  Agbada, Gowns, Suites etc
                </p>
              </div>
            </div>
            <div class="col-lg-3">
              <div class="service_icon icon3 delay-03s animated wow zoomIn">
                <span
                  ><img
                    src="../assets/hand-disinfection-4954840_1920.jpg"
                    alt=""
                  />
                </span>
              </div>
              <div class="service_block">
                <h3 class="animated fadeInUp wow">Disinfection</h3>
                <p class="animated fadeInDown wow">
                  We offer safe disinfection of homes/office spaces using
                  recommended chemicals and procedure Wiping of high touch
                  surfaces across the office/house
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!--Service-->
  </div>
</template>

<script>
export default {
  name: "MainSection",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#service {
  padding: 60px 0px;
  background: #374045;
}

#service h2 {
  color: #fff;
}

.service_wrapper {
  padding: 40px 0 40px;
}

.service_block {
  text-align: center;
  padding-left: 15px;
  padding-right: 15px;
  position: relative;
}

.service_icon {
  width: 80%;
  height: 144px;
  margin: 0px auto 25px;
}

.service_icon span {
  background: transparent;
  display: block;
  height: 100%;
  width: 100%;
  border: 1px solid #fff;
  overflow: hidden;
}

.service_icon i {
  color: #fff;
  font-size: 40px;
  margin-top: 0;
  position: relative;
  top: 20px;
  z-index: 20;
  display: block;
  text-align: center;
}

.service_block h3 {
  font-family: "Raleway", sans-serif;
  font-weight: 600;
  font-size: 25px;
  color: #fff;
  margin: 35px 0 15px;
}

.service_block p {
  font-size: 16px;
  color: #fff;
  margin: 0px;
}
</style>
