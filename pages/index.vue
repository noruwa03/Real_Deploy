<template>
  <div>
    <NavigationBar />
    <!-- Header -->
    <header>
      <div class="container">
        <div class="text-center">
          <h1>
            Building The Next
            <span>Unicorn</span>
            With You
          </h1>

          <p>
            Your trusted partner in building sustainable products for the
            future. Be it blockchain developement, AI, web apps, UI/UX design or
            SaaS. We are on a mission to give your startup a headstart.
          </p>

          <div class="mt-5">
            <a href="#contact" class="anchor-link"> Get a free quote </a>
          </div>
        </div>
      </div>
    </header>
    <!-- End of Header -->

    <!-- Services -->
    <div id="services" class="services">
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
            <div class="service-card my-2">
              <div class="text-center">
                <img src="@/assets/icons/web-app.svg" alt="Web Application" />
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
                <img src="@/assets/icons/saas-app-dev.svg" alt="SaaS App Development" />
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
                <img src="@/assets/icons/mobile-app-dev.svg" alt="Mobile App Development" />
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
                <img src="@/assets/icons/block-dev.svg" alt="Blockchain Development" />
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
                <img src="@/assets/icons/ux-ui-design.svg" alt="UX/UI Design" />
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
                <img src="@/assets/icons/data-science.svg" alt="Data Science & AI Models" />
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
    <div id="about-us" class="about-us">
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
                <img src="@/assets/icons/cutting-edge-tech.svg" alt="Cutting Edge Technology" />
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
                <img src="@/assets/icons/cross-device-comp.svg" alt="Cross Device Compatibility" />
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
                <img src="@/assets/icons/tailor-made-dev.svg" alt="Tailor Made Development" />
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
              src="@/assets/icons/cover-image.jpg"
              class="img-fluid"
              alt="Cover Image"
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
    <!-- <div id="contact" class="contact-us">
      <div class="container-lg">
        <h1 class="pb-4 text-center">Have a project! Let’s discuss</h1>


        <div class="row-item">
          <div class="contact-form">
            <div class="wrapper">
              <form>
                <div class="first-row">
                  <div class="input-data">
                    <input type="text" name="" id="" required />
                    <div class="underline"></div>
                    <label for="">Your Company Name</label>
                  </div>
                </div>
                <div class="first-row" >
                  <div class="input-data">
                    <input type="text" name="" id="" required />
                    <div class="underline"></div>
                    <label for="">Nature of Business</label>
                  </div>
                </div>
     
                <div class="first-row">
                  <div class="input-data">
                    <input type="text" name="" id="" required />
                    <div class="underline"></div>
                    <label for="">Contact Name</label>
                  </div>
                </div>
                <div class="first-row">
                  <div class="input-data">
                    <input type="text" name="" id="" required />
                    <div class="underline"></div>
                    <label for="">Contact Phone</label>
                  </div>
                </div>
                <div class="first-row">
                  <div class="input-data">
                    <input type="text" name="" id="" required />
                    <div class="underline"></div>
                    <label for="">email@gmail</label>
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
                    <img src="@/assets/icons/upload.svg" class="me-3" alt="Upload" />
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
                  
                </div>
              </form>
            </div>
          </div>

          <div class="address">
            <h4>Offices</h4>
            <div>
              United States <span> 30 N Gould St R, Sheridan, WY 82801 </span>
            </div>
            <div>
              Nigeria
              <span> 17 Ozo Ocheoha Street Independence Layout Enugu </span>
            </div>

            <div>Tanzania <span> 1 Morogoro Road, Dar Es Salaam </span></div>

            <h4 class="mt-5">For Quick Inquiries</h4>
            <div class="contact-email">
              <img
                src="@/assets/icons/information.svg"
                class="email-info me-1"
                alt="Information"
              />
              <a href="mailto:contact@ecolabz.io">contact@ecolabz.io</a>
            </div>
          </div>
        </div>
      </div>
    </div> -->
    <!-- End of Contact Us -->
    <Faq/>

    
    <Footer />
  </div>
</template>

<script>
export default {
  setup() {
    // const goto = () => {
    //   const el = document.querySelector("#contact");
    //   el.scrollIntoView(false);
    // };



    return {
  
    };
  },
};

// export default {
//   name: "IndexPage",
// };
</script>
