<template>
  <div>
    <NavigationBar />
    <!-- Header -->
    <header>
      <div class="container">
        <div class="text-center">
          <h1>Building The Next <span>Unicorn</span> With You</h1>
          <p>
            Your trusted partner in building sustainable products for the
            future. Be it blockchain developement, AI, web apps, UI/UX design or
            SaaS. We are on a mission to give your startup a headstart.
          </p>

          <div class="mt-5">
            <span class="anchor-link" @click="goto">
              Get a free quote
            </span>
          </div>
        </div>
      </div>
    </header>
    <!-- End of Header -->

    <!-- Services -->
    <div class="services">
      <div class="text-center mb-5">
        <h2>Our Services</h2>
      </div>
      <div class="container-lg">
        <div
          class="
            row
            align-items-center
            justify-content-between justify-content-sm-around
          "
        >
          <div class="col-lg-4 col-sm-6 col-12">
            <div class="service-card bg-white my-2">
              <div class="text-center">
                <img src="@/assets/images/web-app.svg" alt="" />
                <h3>Web Application</h3>
                <p class="pb-5">
                  Our dedicated development team builds world class products and
                  can improve existing tecnologies.
                </p>
              </div>
            </div>
          </div>
          <div class="col-lg-4 col-sm-6 col-12">
            <div class="service-card my-2">
              <div class="text-center">
                <img src="@/assets/images/saas-app-dev.svg" alt="" />
                <h3>SaaS App Development</h3>
                <p>
                  we create custom SaaS solutions that are market ready,
                  comprehensive, and customer friendly for increased business
                  productivity.
                </p>
              </div>
            </div>
          </div>
          <div class="col-lg-4 col-sm-6 col-12">
            <div class="service-card my-2">
              <div class="text-center">
                <img src="@/assets/images/mobile-app-dev.svg" alt="" />
                <h3 class="pt-2">Mobile App Development</h3>
                <p class="pb-5">
                  We build mobile apps that delight users, run smoothly, and
                  loads faster for both Android and iOS.
                </p>
              </div>
            </div>
          </div>
          <div class="col-lg-4 col-sm-6 col-12">
            <div class="service-card my-2">
              <div class="text-center">
                <img src="@/assets/images/block-dev.svg" alt="" />
                <h3>Blockchain Development</h3>
                <p class="pb-4">
                  Blockchain is the future and our team has the reputation of
                  validating your ideas and building you great products
                </p>
              </div>
            </div>
          </div>

          <div class="col-lg-4 col-sm-6 col-12">
            <div class="service-card my-2">
              <div class="text-center">
                <img src="@/assets/images/ux-ui-design.svg" alt="" />
                <h3>UX/UI Design</h3>
                <p class="pb-4">
                  Our designers bring world class expertise to the table. Making
                  a bold statement from ideation to finished designs.
                </p>
              </div>
            </div>
          </div>
          <div class="col-lg-4 col-sm-6 col-12">
            <div class="service-card my-2">
              <div class="text-center">
                <img src="@/assets/images/data-science.svg" alt="" />
                <h3>Data Science & AI Models</h3>
                <p class="pb-4">
                  Our AI powered systems offers instant analysis of hundreds of
                  data, making meaning of them and helping you draw valuable
                  deductions.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- End of Services -->

    <!-- About Us -->
    <div class="about-us">
      <div class="text-center mb-4">
        <h2>What Makes Ecolabz Different</h2>
        <p class="about-us-desc">
          We are made up of highly trained experts using cutting edge technology
          to validate your ideas, build disruptive products, that achieves your
          business goals.
        </p>
      </div>
      <div class="container-lg">
        <div
          class="
            row
            align-items-center
            justify-content-between justify-content-sm-around
          "
        >
          <div class="col-lg-4 col-sm-6 col-12">
            <div class="about-card my-2">
              <div class="text-center">
                <img src="@/assets/images/cutting-edge-tech.svg" alt="" />
                <h3>Cutting Edge Technology</h3>
                <p class="pb-5">
                  We utilize cutting edge solutions in our web design software
                  product design.
                </p>
              </div>
            </div>
          </div>

          <div class="col-lg-4 col-sm-6 col-12">
            <div class="about-card my-2">
              <div class="text-center">
                <img
                  src="@/assets/images/cross-dev-comp.svg"
                  class="my-4"
                  alt=""
                />
                <h3>Cross Device Compatibility</h3>
                <p class="pb-3">
                  We implement projects end-to-end or augment your existing team
                  to complete any work that may be needed.
                </p>
              </div>
            </div>
          </div>

          <div class="col-lg-4 col-sm-6 col-12">
            <div class="about-card my-2">
              <div class="text-center">
                <img src="@/assets/images/clock.svg" alt="" />
                <h3>Tailor Made Development</h3>
                <p class="pb-1">
                  We develop products from the idea stage using scalable and
                  dynamic systems to meet up to ever changing trends.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- End of About Us -->

    <!-- Latest News -->
    <div class="latest-news">
      <h1 class="text-center">Latest news from us</h1>

      <p class="text-center">
        Stay up to date with happenings in the tech world
      </p>

      <div class="container-lg">
        <div class="row align-items-center justify-content-between">
          <div class="col-12 mt-sm-5 mt-3">
            <img
              src="@/assets/images/cover-image.jpg"
              class="img-fluid"
              alt=""
            />
          </div>
        </div>
      </div>
    </div>
    <!-- End of Latest News -->

    <!-- Our Approach -->
    <div class="our-approach">
      <div class="heading text-center mb-4">
        <h4>Our approach to delivering great services</h4>
      </div>
      <div class="container-lg">
        <div
          class="
            row
            align-items-center
            justify-content-lg-between justify-content-sm-around
          "
        >
          <div class="col-lg-4 col-sm-6 col-12">
            <div class="approach-card my-2">
              <h5 class="text-center">In-depth Research & Development:</h5>
              <p class="text-center">
                Our approach to design and product development involves a
                thorough research of the market, the users, stakeholders, trends
                and future expectation that will result in useable product.
              </p>
            </div>
          </div>
          <div class="col-lg-4 col-sm-6 col-12">
            <div class="approach-card my-2">
              <h5 class="text-center">Intuitive Design</h5>
              <p class="pt-4 pb-5 text-center">
                Our products are designed to be accessible, intuitive, and
                usable. Sophisticated enough for tech savvy users and simple for
                casual users.
              </p>
            </div>
          </div>
          <div class="col-lg-4 col-sm-6 col-12">
            <div class="approach-card my-2">
              <h5 class="text-center">Excellent Services</h5>
              <p class="text-center">
                We believe that great products speaks for themselves and help
                you reach your business goals faster. On this, rest our mission
                of delivering highest quality service. We research, test run,
                reiterate, run QA and review before delivering your projects.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- End of Our Approach -->

    <!-- Valuable Insight -->
    <!-- <div class="valuable-insight">
      <div class="container-lg">
        <div class="row align-items-center justify-content-between">
          <div class="col-sm-6 col-12">
            <h1>Latest Valuable Insights</h1>
          </div>
          <div class="col-sm-6 col-12">
            <p>
              Lorem ipsum dolor sit, amet consectetur adipisicing elit. Deserunt
              facilis laborum reprehenderit earum sit sunt ratione blanditiis
              sint. Molestias veniam minus rem, cum inventore culpa omnis eaque
              excepturi? Ea, ab.
            </p>
          </div>

          <div class="col-12 mt-sm-5 mt-3">
            <img
              src="@/assets/images/cover-image.jpg"
              class="img-fluid"
              alt=""
            />
          </div>
        </div>
      </div>
    </div> -->
    <!-- End of Valuable Insight -->

    <!-- Contact Us -->
    <div class="contact-us" id="contact"  >
      <div class="container-lg">
        <h1 class="pb-4">Got a project or partnership in mind?</h1>
        <!-- <p>
          Need an experienced and skilled hand with custom IT projects?
          <span>Fill out the form to get a free consultation.</span>
        </p> -->

        <div class="row-item" >
          <div class="contact-form">
            <div class="wrapper">
              <form >
                <div class="first-row">
                  <div class="input-data">
                    <input type="text" name="" id="" required />
                    <div class="underline"></div>
                    <label for="">Your company name</label>
                  </div>
                </div>
                <div class="first-row">
                  <div class="input-data">
                    <input type="text" name="" id="" required />
                    <div class="underline"></div>
                    <label for="">Nature of business</label>
                  </div>
                </div>
                <div class="form-row">
                  <div class="address">
                    <input type="text" name="" id="" required />
                    <div class="underline"></div>
                    <label for="">Address</label>
                  </div>
                  <div class="post-code">
                    <input type="text" name="" id="" required />
                    <div class="underline"></div>
                    <label for="">Post code</label>
                  </div>
                </div>
                <div class="first-row">
                  <div class="input-data">
                    <input type="text" name="" id="" required />
                    <div class="underline"></div>
                    <label for="">Contact name</label>
                  </div>
                </div>
                <div class="first-row">
                  <div class="input-data">
                    <input type="text" name="" id="" required />
                    <div class="underline"></div>
                    <label for="">Contact phone</label>
                  </div>
                </div>
                <div class="first-row">
                  <div class="input-data">
                    <input type="text" name="" id="" required />
                    <div class="underline"></div>
                    <label for="">Email</label>
                  </div>
                </div>
                <div class="first-row">
                  <div class="input-data">
                    <input type="text" name="" id="" required />
                    <div class="underline"></div>
                    <label for="">LinkedIn</label>
                  </div>
                </div>
                <div class="first-row">
                  <div class="input-data">
                    <input type="text" name="" id="" required />
                    <div class="underline"></div>
                    <label for="">Let's talk about your ideas</label>
                  </div>
                </div>

                <div class="file-box">
                  <div>
                    <img src="@/assets/images/upload.svg" class="me-3" alt="" />
                    <span>Upload Additional file</span>
                  </div>
                </div>
                <p class="upload-instruction">
                  Attach file, Fill size of your documents should not exceed
                  10MB
                </p>

                <button>Submit</button>
                <div class="">
                  <span class="nda"
                    ><input type="checkbox" class="me-1" /> I want to protect my
                    data by signing an NDA</span
                  >
                  <!-- <span class="nda"></span> -->
                </div>
              </form>
            </div>
          </div>

          <div class="address">
            <h4>Offices</h4>
            <div>
              United States <span> 30 N Gould St R, Sheridan, WY 82801 </span>
            </div>
            <div>Nigeria <span> 17 Ozo Ocheoha Street Independence Layout Enugu </span></div>

            <div>
              Tanzania <span> 1 Morogoro Road, Dar Es Salaam </span>
            </div>

            <h4 class="mt-5">For Quick Inquiries</h4>
            <div>
              <img src="@/assets/images/uk-flag.jpg" class="me-2" alt="" /> +44
              7777777777
            </div>
            <div>
              <img src="@/assets/images/usa-flag.jpg" class="me-2" alt="" /> +1
              3333333330
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- End of Contact Us -->
    <Footer />
  </div>
</template>

<script>


export default {
  setup() {
    
    const goto = () => {
      const el = document.querySelector("#contact");
      el.scrollIntoView(false);
      
    };
    
    return {
      goto,
    };
  },
};

// export default {
//   name: "IndexPage",
// };
</script>
