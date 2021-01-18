<template>
    <div>
 <section id="aboutUs">

    <div class="inner_wrapper aboutUs-container fadeInLeft animated wow">
      <div class="container">
        <h2>About Us</h2>
        <h6>Lorem ipsum dolor sit amet, consectetur Morbi sagittis, sem quisci ipsum</h6>
        <div class="inner_section">

          <div class="row">
            <div class="col-lg-12 about-us">
              <div class="row">
             
                <div class="col-md-6">
                  <h3>We Make your Homes more beutiful</h3>
                  <p>
                    Lorem ipsum dolor sit amet, consectetur Morbi sagittis, sem quisci ipsum gravida tortor orci ipsum
                    gravida tortor. Lorem ipsum dolor sit amet, consectetur.
                  </p>

                  <ul class="about-us-list">
                    <li class="points">Consectetur Morbi sagittis, sem quisci ipsum gravida tortor</li>
                    <li class="points">Morbi sagittis, sem quis lacinia faucibus, orci ipsum gravida </li>
                    <li class="points">Lorem ipsum dolor sit amet, consectetur Morbi sagittis, sem quisci gravida </li>
                    <li class="points">Sagittis, sem quis lacinia faucibus, orci ipsum gravida </li>
                    <li class="points">Ipsum dolor sit amet, consectetur Morbi sagittis, sem quisci</li>
                  </ul>
                </div>

                <div class="col-md-6">
                 <!-- <img src="img/dinning-room-695074.jpg" alt="" class="container-fluid"> -->
                 <div class="wrapper">
                    <div class="pic-ctn">
                      <img src="../assets/dinning-room-695074.jpg" alt="" class="pic">
                      <img src="../assets/1.jpg" alt="" class="pic">
                      <img src="../assets/2.jpg" alt="" class="pic">
                      <img src="../assets/3.jpg" alt="" class="pic">
                      <img src="../assets/furniture-998265_1920.jpg" alt="" class="pic">
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

.pic-ctn>img {
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
