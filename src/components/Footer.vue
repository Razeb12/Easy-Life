<template>
  <div>
    <!--Footer-->
    <footer class="footer_wrapper" id="contact">
      <div class="container">
        <section class="page_section contact" id="contact">
          <div class="contact_section">
            <h2>Contact Us</h2>
            <div class="row">
              <div class="col-lg-4"></div>
              <div class="col-lg-4"></div>
              <div class="col-lg-4"></div>
            </div>
          </div>
          <div class="row">
            <div class="col-lg-4 wow fadeInLeft">
              <div class="contact_info">
                <div class="detail">
                  <h4>Restore Service Head Quarters</h4>
                  <p>Peter Odili Road, Port Harcourt, Nigeria</p>
                </div>
                <div class="detail">
                  <h4>Call us ?</h4>
                  <p>08138508192</p>
                </div>
                <div class="detail">
                  <h4>Email us</h4>
                  <p>support@restoreservices.com</p>
                </div>
              </div>

              <ul class="social_links">
                <li class="twitter animated bounceIn wow delay-02s">
                  <a href="javascript:void(0)"><i class="fa fa-twitter"></i></a>
                </li>
                <li class="facebook animated bounceIn wow delay-03s">
                  <a href="javascript:void(0)"
                    ><i class="fa fa-facebook"></i
                  ></a>
                </li>
                <li class="pinterest animated bounceIn wow delay-04s">
                  <a href="javascript:void(0)"
                    ><i class="fa fa-pinterest"></i
                  ></a>
                </li>
                <li class="gplus animated bounceIn wow delay-05s">
                  <a href="javascript:void(0)"
                    ><i class="fa fa-google-plus"></i
                  ></a>
                </li>
              </ul>
            </div>
            <div class="col-lg-8 wow fadeInLeft delay-06s">
              <div class="form">
                <input
                  class="input-text"
                  type="text"
                  name=""
                  value="Your Name *"
                  onFocus="if(this.value==this.defaultValue)this.value='';"
                  onBlur="if(this.value=='')this.value=this.defaultValue;"
                />
                <input
                  class="input-text"
                  type="text"
                  name=""
                  value="Your E-mail *"
                  onFocus="if(this.value==this.defaultValue)this.value='';"
                  onBlur="if(this.value=='')this.value=this.defaultValue;"
                />
                <textarea
                  class="input-text text-area"
                  cols="0"
                  rows="0"
                  onFocus="if(this.value==this.defaultValue)this.value='';"
                  onBlur="if(this.value=='')this.value=this.defaultValue;"
                >
Your Message *</textarea
                >
                <input class="input-btn" type="submit" value="send message" />
              </div>
            </div>
          </div>
        </section>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style scoped>
.page_section.contact {
  padding: 90px 0 100px;
}

.contact_section {
  margin: 0 0 60px 0;
}

.contact_section h2 {
  font-size: 40px;
  color: #ffffff;
  margin: 0 0 50px 0;
  text-transform: uppercase;
}

.contact_block {
  text-align: center;
}

.contact_block_icon {
  border-radius: 50%;
  height: 85px;
  width: 85px;
  margin: 0px auto 20px;
}

.contact_block_icon.icon2 {
  border-color: #efb21d;
}

.contact_block_icon.icon3 {
  border-color: #49b5e7;
}

.contact_block_icon span {
  background: none repeat scroll 0 0 #f56eab;
  border: 5px solid #fff;
  border-radius: 50%;
  display: block;
  height: 100%;
  width: 100%;
}

.contact_block_icon.icon2 {
  border-color: #efb21d;
}

.contact_block_icon.icon2 span {
  background: #efb21d;
}

.contact_block_icon.icon3 {
  border-color: #49b5e7;
}

.contact_block_icon.icon3 span {
  background: #49b5e7;
}

.contact_block_icon i {
  color: #fff;
  font-size: 36px;
  margin-top: 0;
  position: relative;
  top: 26px;
  z-index: 20;
}

.contact_block span {
  display: block;
  font-size: 16px;
  color: #ffffff;
  line-height: 20px;
}

.contact_block span a {
  display: block;
  font-size: 16px;
  color: #ffffff;
  line-height: 20px;
}

.contact_info {
  font-size: 15px;
  margin: 0 0 0 20px;
  padding-left: 0;
}

.contact_info h3 {
  font-size: 24px;
  font-weight: 600;
  margin: 0 0 30px;
  color: #fff;
}

.contact_info p {
  line-height: 28px;
  display: block;
  font-size: 16px;
  color: #ffffff;
  margin: 0 0 30px;
}

.social_links {
  padding: 0;
  margin: 0;
  display: block;
  overflow: hidden;
  list-style: none;
}

.social_links li {
  float: left;
  margin-right: 4px;
}

.social_links li a {
  display: block;
  width: 50px;
  height: 50px;
  text-align: center;
  line-height: 50px;
  font-size: 25px;
  color: #fff;
}

.social_links li a:hover,
.social_links li a:focus {
  text-decoration: none;
  border-radius: 80px;
}

.twitter a:hover {
  color: #55acee;
}

.facebook a:hover {
  color: #3b5998;
}

.pinterest a:hover {
  color: #cb2026;
}

.gplus a:hover {
  color: #dd4b39;
}

.form {
  margin: 0 66px 0 30px;
}

.input-text {
  padding: 15px 16px;
  border: 1px solid #ccc;
  width: 100%;
  height: 50px;
  display: block;
  border-radius: 4px;
  font-size: 15px;
  color: #aaa;
  margin: 0 0 15px 0;
  transition: all 0.3s ease-in-out;
  -moz-transition: all 0.3s ease-in-out;
  -webkit-transition: all 0.3s ease-in-out;
}

.input-text:focus {
  border: 1px solid #fff;
  outline: 0;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075),
    0 0 8px rgba(124, 197, 118, 0.3);
  -moz-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075),
    0 0 8px rgba(124, 197, 118, 0.3);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075),
    0 0 8px rgba(124, 197, 118, 0.3);
}

.input-text.text-area {
  height: 230px;
  resize: none;
  overflow: auto;
}

.input-btn {
  width: 175px;
  height: 50px;
  letter-spacing: 0px;
  background: #efb21d;
  border-radius: 3px;
  color: #ffffff;
  font-size: 16px;
  text-transform: uppercase;
  font-weight: 600;
  border: 0px;
  transition: all 0.3s ease-in-out;
  -moz-transition: all 0.3s ease-in-out;
  -webkit-transition: all 0.3s ease-in-out;
}

.input-btn:hover {
  background: #fff;
  color: #222;
}

/* Footer
---------------------------------*/

.footer_wrapper {
  background: #374045;
}

.footer_bottom {
  border-top: 1px solid #3c3a3a;
  padding: 25px 0;
}

.footer_bottom span {
  display: block;
  font-size: 14px;
  color: #cccccc;
  text-align: center;
}

.footer_bottom span a {
  display: inline-block;
  color: #efb21d;
  font-size: 16px;
  transition: all 0.3s ease-in-out;
  -moz-transition: all 0.3s ease-in-out;
  -webkit-transition: all 0.3s ease-in-out;
}

.footer_bottom span a:hover {
  color: #fff;
}
</style>