<template>
  <div>
    <section id="aboutUs">
      <div class="inner_wrapper aboutUs-container fadeInLeft animated wow">
        <div class="container">
          <h2>About Us</h2>
          <h6>
            We are a Port Harcourt Based Company with a passion for helping
            clients who may be otherwise too busy to keep their houses in shape.
            We will bear that responsibility of restoring your home/offices
            spaces into great working conditions.
          </h6>
          <div class="inner_section">
            <div class="row">
              <div class="col-lg-12 about-us">
                <div class="row">
                  <div class="col-md-6">
                    <h3>Our Potential Clients</h3>

                    <ul class="about-us-list">
                      <li class="points">
                        Does your work take you away from home so long and you
                        come back to meet a mess ?
                      </li>
                      <li class="points">
                        Having windows clogged with soot due to inability to
                        keep up with the maintenance and external pollution ?
                      </li>
                      <li class="points">
                        Would you like professional laundry service that starts
                        from home-pick up and delivery of your laundry items at
                        an affordable fee ?
                      </li>
                      <li class="points">
                        Would you like to get rid of bed-bugs, roaches that have
                        infested your home/office space ?
                      </li>
                    </ul>
                  </div>

                  <div class="col-md-6">
                    <!-- <img src="img/dinning-room-695074.jpg" alt="" class="container-fluid"> -->
                    <div class="wrapper">
                      <div class="pic-ctn">
                        <img
                          src="../assets/dinning-room-695074.jpg"
                          alt=""
                          class="pic"
                        />
                        <img src="../assets/1.jpg" alt="" class="pic" />
                        <img src="../assets/2.jpg" alt="" class="pic" />
                        <img src="../assets/3.jpg" alt="" class="pic" />
                        <img
                          src="../assets/furniture-998265_1920.jpg"
                          alt=""
                          class="pic"
                        />
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: "AboutUs",
};
</script>


<style>
.aboutUs-container {
  background-repeat: no-repeat;
  background-position: right;
  background-size: auto 100%;
  background-position-y: 70px;
}

#about-us .read-more {
  border: 1px solid #efb21d;
  color: #1a1a1a;
}

#about-us .read-more:hover {
  background-color: #e74c3c;
  border: 1px solid #e74c3c;
  color: #fff;
}

.about-us-post-container {
  background-repeat: no-repeat;
  background-position: right;
  background-size: auto 100%;
}

.about-us {
  margin-top: 50px;
  margin-bottom: 50px;
}

.about-us h3 {
  font-size: 28px;
}

.points {
  margin-bottom: 10px;
  font-size: 14px;
  padding-left: 0px;
}

.about-us p {
  /*font-size: 0.9375em;*/
  line-height: 1.625em;
  padding: 15px 0;
}

.about-us .about-us-list {
  list-style: none;
  margin-bottom: 20px;
  padding-left: 0px;
}

.about-us .points {
  position: relative;
  list-style-type: none;
  padding: 5px 0 5px 30px;
}

.about-us .points:before {
  content: "\f058";
  position: absolute;
  font-family: FontAwesome;
  font-size: 1.125em;
  color: #efb21d;
  left: 0px;
  top: 3px;
}

.about-us-link a:first-child {
  margin-left: 0;
}
#aboutUs {
  padding: 60px 0;
}
.pic-ctn {
  width: 100vw;
  height: 200px;
}

@keyframes display {
  0% {
    transform: translateX(200px);
    opacity: 0;
  }

  10% {
    transform: translateX(0);
    opacity: 1;
  }

  20% {
    transform: translateX(0);
    opacity: 1;
  }

  30% {
    transform: translateX(-200px);
    opacity: 0;
  }

  100% {
    transform: translateX(-200px);
    opacity: 0;
  }
}
.pic-ctn {
  position: relative;
  width: 100vw;
  height: 300px;
  /* margin-top: 15vh; */
}

.pic-ctn > img {
  position: absolute;
  top: 0;
  left: calc(50% - 100px);
  opacity: 0;
  animation: display 20s infinite;
}

img:nth-child(2) {
  animation-delay: 4s;
}

img:nth-child(3) {
  animation-delay: 8s;
}

img:nth-child(4) {
  animation-delay: 12s;
}

img:nth-child(5) {
  animation-delay: 16s;
}
img {
  max-width: 100%;
}
@media (max-width: 768px) {
  img.pic {
    height: 100%;
  }
}
</style>
