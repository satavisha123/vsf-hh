<template>
  <div>
    <div>
      <div class="Footer-row Footer-row--top">
        <div>
          <div class="Footer-cell">
            <div class="Footer-newsletter">
              <h2>Stay in the know with exclusive deals and event updates.</h2>
              <form action="post">
                <label for="Footer-newsletter-email">Email address</label>
                <input
                  type="email"
                  placeholder="Email address"
                  name="email"
                  id="Footer-newsletter-email"
                  required=""
                />

                <input type="submit" class="Button" value="Sign Up" />
              </form>
            </div>
          </div>
          <div class="Footer-cell">
            <div class="Footer-social">
              <!-- <h2>Inspiration’s always handy</h2>
        <p>Follow us for bright ideas and must-haves for every season.</p> -->
              <!-- COMPONENT: SocialLinks -->
              <!-- <ul class="SocialLinks ">
          <li>
            <a href="#" data-facebook="">
              <span>Facebook</span>
            </a>
          </li>
          <li>
            <a href="#" data-twitter="">
              <span>Twitter</span>
            </a>
          </li>
          <li>
            <a href="#" data-pinterest="">
              <span>Pinterest</span>
            </a>
          </li>
          <li>
            <a href="#" data-youtube="">
              <span>Youtube</span>
            </a>
          </li>
          <li>
            <a href="#" data-instagram="">
              <span>Instagram</span>
            </a>
          </li>
        </ul> -->
              <!-- /COMPONENT: SocialLinks -->
            </div>
          </div>
        </div>
      </div>
      <div class="Footer-row Footer-row--middle">
        <div class="Footer-cell">
          <div class="Footer-services">
            <nav>
              <ul class="footer-icons">
                <li>
                  <a href="#">
                    <img
                      src="https://hh-styleguide.s3.ca-central-1.amazonaws.com/img/ui/footer/servies/aeroplan-en.png"
                      alt=""
                      class="footer-image"
                    />
                    <span>Earn Aeroplan Miles</span>
                  </a>
                </li>
                <li>
                  <a href="#">
                    <img
                      src="https://hh-styleguide.s3.ca-central-1.amazonaws.com/img/ui/footer/servies/beautitone-en.png"
                      alt=""
                      class="footer-image"
                    />
                    <span>Earn free paint</span>
                  </a>
                </li>
                <li>
                  <a href="#">
                    <img
                      src="https://hh-styleguide.s3.ca-central-1.amazonaws.com/img/ui/footer/servies/giftcards-en.png"
                      alt=""
                      class="footer-image"
                    />
                    <span>Give a give card</span>
                  </a>
                </li>
                <li>
                  <a href="#">
                    <img
                      src="https://hh-styleguide.s3.ca-central-1.amazonaws.com/img/ui/footer/servies/contractors-en.png"
                      alt=""
                      class="footer-image"
                    />
                    <span>Earn contractor rewards</span>
                  </a>
                </li>
                <li>
                  <a href="#">
                    <img
                      src="https://hh-styleguide.s3.ca-central-1.amazonaws.com/img/ui/footer/servies/beaverhomes-en.png"
                      alt=""
                      class="footer-image"
                    />
                    <span>Beaver Homes &amp; Cottages</span>
                  </a>
                </li>
              </ul>
            </nav>
          </div>
        </div>
        <div class="Footer-cell">
          <div class="Footer-navigation">
            <ul class="TabList" role="tablist">
              <li class="for-service">
                <h2
                  role="tab"
                  aria-selected="false"
                  aria-expanded="false"
                  aria-controls="Footer-navigation-1-panel"
                  id="Footer-navigation-1-tab"
                  tabindex="0"
                >
                  Services
                </h2>
                <ul
                  role="tabpanel"
                  aria-hidden="true"
                  aria-labelledby="Footer-navigation-1-tab"
                  id="Footer-navigation-1-panel"
                  tabindex="-1"
                >
                  <li class="footerlistitem">
                    <a href="#">Home Install</a>
                  </li>
                  <li class="footerlistitem">
                    <a href="#">Home Rentals - Equipment Rental</a>
                  </li>
                  <li class="footerlistitem">
                    <a href="#">Rental</a>
                  </li>
                </ul>
              </li>
              <li class="for-Business">
                <h2
                  role="tab"
                  aria-selected="false"
                  aria-expanded="false"
                  aria-controls="Footer-navigation-2-panel"
                  id="Footer-navigation-2-tab"
                  tabindex="0"
                >
                  Services for Business
                </h2>
                <ul
                  role="tabpanel"
                  aria-hidden="true"
                  aria-labelledby="Footer-navigation-2-tab"
                  id="Footer-navigation-2-panel"
                  tabindex="-1"
                >
                  <li class="footerlistitem">
                    <a href="#">Commercial Maintenance</a>
                  </li>
                  <li class="footerlistitem">
                    <a href="#">HH Pro - Contractor Services</a>
                  </li>
                </ul>
              </li>
              <li>
                <h2
                  role="tab"
                  aria-selected="false"
                  aria-expanded="false"
                  aria-controls="Footer-navigation-3-panel"
                  id="Footer-navigation-3-tab"
                  tabindex="0"
                >
                  About Us
                </h2>
                <ul
                  role="tabpanel"
                  aria-hidden="true"
                  aria-labelledby="Footer-navigation-3-tab"
                  id="Footer-navigation-3-panel"
                  tabindex="-1"
                >
                  <li class="footerlistitem">
                    <a href="#">Become a Dealer</a>
                  </li>
                  <li class="footerlistitem">
                    <a href="#">About Home Hardware</a>
                  </li>
                  <li class="footerlistitem">
                    <a href="#">Careers</a>
                  </li>
                  <li class="footerlistitem">
                    <a href="#">Home at Home</a>
                  </li>
                  <li class="footerlistitem">
                    <a href="#">Store Locator</a>
                  </li>
                  <li class="footerlistitem">
                    <a href="#">Supplier Guide</a>
                  </li>
                </ul>
              </li>
              <li>
                <h2
                  role="tab"
                  aria-selected="false"
                  aria-expanded="false"
                  aria-controls="Footer-navigation-4-panel"
                  id="Footer-navigation-4-tab"
                  tabindex="0"
                >
                  Help &amp; Support
                </h2>
                <ul
                  role="tabpanel"
                  aria-hidden="true"
                  aria-labelledby="Footer-navigation-4-tab"
                  id="Footer-navigation-4-panel"
                  tabindex="-1"
                >
                  <li class="footerlistitem">
                    <a href="#">Return Policy</a>
                  </li>
                  <li class="footerlistitem">
                    <a href="#">Shipping</a>
                  </li>
                  <li class="footerlistitem">
                    <a href="#">Product Recalls</a>
                  </li>
                  <li class="footerlistitem">
                    <a href="#">Website Pricing</a>
                  </li>
                  <li class="footerlistitem">
                    <a href="#">FAQs</a>
                  </li>
                  <li class="footerlistitem">
                    <a href="#">Contact Us</a>
                  </li>
                </ul>
              </li>
            </ul>
          </div>
        </div>
      </div>
      <div class="Footer-accessibility">
        <h2>Accessibility Support</h2>
        <div>
          <a href="https://www.essentialaccessibility.com/" target="_blank">
            <span>Download the app</span>
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import { SfFooter, SfList, SfImage, SfMenuItem } from "@storefront-ui/vue";

export default {
  components: {
    SfFooter,
    SfList,
    SfImage,
    SfMenuItem,
  },
  data() {
    return {
      aboutUs: ["Who we are", "Quality in the details", "Customer Reviews"],
      departments: ["Women fashion", "Men fashion", "Kidswear", "Home"],
      help: ["Customer service", "Size guide", "Contact us"],
      paymentsDelivery: ["Purchase terms", "Guarantee"],
      social: ["facebook", "pinterest", "google", "twitter", "youtube"],
      isMobile: false,
      desktopMin: 1024,
    };
  },
};
</script>

<style  >
/* @import "//fonts.googleapis.com/css?family=Work+Sans:400,500,700"; */
@import "//cdnjs.cloudflare.com/ajax/libs/material-design-iconic-font/2.2.0/css/material-design-iconic-font.min.css";
/* @import "//hh-styleguide.s3.ca-central-1.amazonaws.com/css/bootstrap3.7.css";
@import "//hh-styleguide.s3.ca-central-1.amazonaws.com/css/app.css";
@import "//hh-styleguide.s3.ca-central-1.amazonaws.com/css/utilities.css";  */

.Footer-row {
  padding: 30px 0;
}
.Footer-row--top {
  background-color: #e4002b;
  color: #fff;
}
.Footer-row--middle {
  display: grid;
  grid-template-columns: 1fr 2fr;
  padding-left: 100px;
  padding-right: 100px;
  padding-top: 70px;
}
.TabList {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  list-style: none;
 
  font-size: 15px;
}

#Footer-navigation-1-tab,
#Footer-navigation-2-tab,
#Footer-navigation-3-tab,
#Footer-navigation-4-tab {
  margin: 1px 1px;
  font-family: "Agenda_bold", sans-serif;
  font-style: normal;
  /* font-weight: normal; */
  font-size: 18px;
}

#Footer-navigation-1-panel {
  list-style: none;
  padding: 0px;
 text-decoration: underline;
}
#Footer-navigation-2-panel {
  list-style: none;
  padding: 0px;
  text-decoration: underline;
}
#Footer-navigation-3-panel {
  list-style: none;
  padding: 0px;
  text-decoration: underline;
}
#Footer-navigation-4-panel {
  list-style: none;
  padding: 0px;
  text-decoration: underline;
}
#Footer-navigation-1-panel:hover{
  color: red;
}
.for-service {
  grid-column: 1 / 1;
  grid-row: 1/1;
}
.for-Business {
  grid-column: 1/2;
  grid-row: 2/2;
}
.footer-icons {
  list-style: none;
}
.footer-image {
  width: 97px;
  height: 50px;
  padding-right: 9px;
}
.footerlistitem{
  padding-bottom: 8px;
}
</style>