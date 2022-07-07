<template>
  <div>
    <NavigationBar />
    <div class="contact-page">
      <h1 class="text-center">Get a project quote</h1>
      <div class="text-center box my-3">
        <p>
          Please fill the form below to receive a quote for your project. Feel
          free to add as much detail as needed.
        </p>
      </div>
      <div class="contact-card">
        <div class="progress-bar">
          <div class="step">
           
            <div class="bullet">
              <span>1</span>
            </div>
          </div>

          <div class="step">
            
            <div class="bullet">
              <span>2</span>
            </div>
          </div>

          <div class="step">
           
            <div class="bullet">
              <span>3</span>
            </div>
          </div>

          <div class="step">
           
            <div class="bullet">
              <span>4</span>
            </div>
          </div>
        </div>
        <div class="divider"></div>

        <div class="form-outer">
          <form>
            <!-- One -->
            <div class="page slidepage">
              <div class="title mt-4">Contact details</div>
              <div class="subtitle mt-2 mb-4">
                Lorem ipsum dolor sit amet consectetur adipisc.
              </div>

              <div class="form-field-row">
                <div class="form-field">
                  <label for="" class="my-3">Name</label>
                  <input type="text" placeholder="John Carter" class="person" />
                  <!-- <span class="person"></span> -->
                </div>

                <div class="form-field">
                  <label for="" class="my-3">Email</label>
                  <input
                    type="text"
                    placeholder="Email address"
                    class="email"
                  />
                  <!-- <span class="email"></span> -->
                </div>
              </div>

              <div class="form-field-row">
                <div class="form-field">
                  <label for="" class="my-3">Phone Number</label>
                  <input
                    type="text"
                    placeholder="(123) 456 - 7890"
                    class="phone"
                  />
                  <!-- <span class="phone"></span> -->
                </div>

                <div class="form-field">
                  <label for="" class="my-3">Company</label>
                  <input
                    type="text"
                    placeholder="Company name"
                    class="company"
                  />
                  <!-- <span class="company"></span> -->
                </div>
              </div>
              <div class="first-page-next">
                <div class="next-step" @click="firstNextBtn">Next step</div>
              </div>
            </div>

            <!-- Two  -->
            <div class="page slidepage">
              <div class="title mt-4">Our services</div>
              <div class="subtitle mt-2 mb-4">
                Please select which service you are interested in.
              </div>

             <div class="second-form">
               <div class="form-item">
                <input
                  type="checkbox"
                  id="checkbox-1"
                  name="checkbox"
                  class="form-input"
                />
                <label for="checkbox-1"  class="form-label">
                  <div class="form-content">
                    <img
                      src="@/assets/images/dev.svg"
                      class="form-img"
                      alt=""
                    />
                    <span class="form-name ms-3">Development</span>
                  </div>
                </label>
              </div>

               <div class="form-item">
                <input
                  type="checkbox"
                  id="checkbox-2"
                  name="checkbox"
                  class="form-input"
                />
                <label for="checkbox-2"  class="form-label">
                  <div class="form-content">
                    <img
                      src="@/assets/images/web-design.svg"
                      class="form-img"
                      alt=""
                    />
                    <span class="form-name ms-3">Web Design</span>
                  </div>
                </label>
              </div>

               <div class="form-item">
                <input
                  type="checkbox"
                  id="checkbox-3"
                  name="checkbox"
                  class="form-input"
                />
                <label for="checkbox-3" class="form-label">
                  <div class="form-content">
                    <img
                      src="@/assets/images/marketing.svg"
                      class="form-img"
                      alt=""
                    />
                    <span class="form-name ms-3">Marketing</span>
                  </div>
                </label>
              </div>

               <div class="form-item">
                <input
                  type="checkbox"
                  id="checkbox-4"
                  name="checkbox"
                  class="form-input"
                />
                <label for="checkbox-4"  class="form-label">
                  <div class="form-content">
                    <img
                      src="@/assets/images/setting.svg"
                      class="form-img"
                      alt=""
                    />
                    <span class="form-name ms-3">Other</span>
                  </div>
                </label>
              </div>

             </div>

              <div class="second-page-next">
                <div class="prev-step" @click="prevBtnSec">Previous step</div>
                <div class="next-step" @click="nextBtnSec">Next step</div>
              </div>
            </div>

            <!-- Three -->

            <div class="page slidepage">
               <div class="title mt-4">What’s your project budget?</div>
              <div class="subtitle mt-2 mb-4">
                Please select the project budget range you have in mind.
              </div>

             <div class="third-form">
               <div class="form-item">
                <input
                  type="checkbox"
                  id="third-checkbox-1"
                  name="budget"
                  class="form-input"
                />
                <label for="third-checkbox-1"  class="form-label">
                  <div class="form-content">
                   
                    <span class="form-name ms-5">$5.000 - $10.000</span>
                  </div>
                </label>
              </div>

               <div class="form-item">
                <input
                  type="checkbox"
                  id="third-checkbox-2"
                  name="budget"
                  class="form-input"
                />
                <label for="third-checkbox-2"  class="form-label">
                  <div class="form-content">
                   
                    <span class="form-name ms-5">$10.000 - $20.000</span>
                  </div>
                </label>
              </div>

               <div class="form-item">
                <input
                  type="checkbox"
                  id="third-checkbox-3"
                  name="budget"
                  class="form-input"
                />
                <label for="third-checkbox-3" class="form-label">
                  <div class="form-content">
                   
                    <span class="form-name ms-5">$20.000 - $50.000</span>
                  </div>
                </label>
              </div>

               <div class="form-item">
                <input
                  type="checkbox"
                  id="third-checkbox-4"
                  name="budget"
                  class="form-input"
                />
                <label for="third-checkbox-4"  class="form-label">
                  <div class="form-content">
                   
                    <span class="form-name ms-5">$50.000 +</span>
                  </div>
                </label>
              </div>

             </div>
              <div class="second-page-next">
                <div class="prev-step" @click="prevBtnThird">Previous step</div>
                <div class="next-step" @click="nextBtnThird">Next step</div>
              </div>
            </div>

            <!-- Four -->

            <div class="page slidepage">
              <div class="text-center  mt-4">
                <img src="@/assets/images/submit.svg" alt="">
              </div>

               <h3 class="text-center submit-quote">Submit your quote request</h3>

              <div class="text-center submit-review">
                Please review all the information you previously typed in the past steps, and if all is okay, submit your message to receive a project quote in 24 - 48 hours.
              </div>

             

              <div class="last-page-next">
                <div class="prev-step" @click="prevBtnFourth">Previous step</div>
                <div class="next-step" @click="submit">Submit</div>
              </div>
            </div>
          </form>
        </div>
      </div>
    </div>
    <Footer />
  </div>
</template>

<script>
export default {
  setup() {
    let max = 4;
    let current = 1;

    const firstNextBtn = () => {
      const slidePage = document.querySelector(".slidepage");

      // const progressText = document.querySelector(".step p");
      // const progressCheck = document.querySelector(".step .check");
      const bullet = document.querySelectorAll(".step .bullet");

      slidePage.style.marginLeft = "-25%";
      bullet[current - 1].classList.add("active");
      current += 1;
    };

    const nextBtnSec = () => {
      const slidePage = document.querySelector(".slidepage");
      const bullet = document.querySelectorAll(".step .bullet");

      slidePage.style.marginLeft = "-50%";
      bullet[current - 1].classList.add("active");
      current += 1;
    };

    const nextBtnThird = () => {
      const slidePage = document.querySelector(".slidepage");
      const bullet = document.querySelectorAll(".step .bullet");

      slidePage.style.marginLeft = "-75%";

      bullet[current - 1].classList.add("active");
      current += 1;
    };

    const prevBtnSec = () => {
      const slidePage = document.querySelector(".slidepage");
      slidePage.style.marginLeft = "0%";

      const bullet = document.querySelectorAll(".step .bullet");

      bullet[current - 2].classList.remove("active");
      current -= 1;
    };

    const prevBtnThird = () => {
      const slidePage = document.querySelector(".slidepage");
      slidePage.style.marginLeft = "-25%";

      const bullet = document.querySelectorAll(".step .bullet");

      bullet[current - 2].classList.remove("active");
      current -= 1;
    };

    const prevBtnFourth = () => {
      const slidePage = document.querySelector(".slidepage");
      slidePage.style.marginLeft = "-50%";

      const bullet = document.querySelectorAll(".step .bullet");

      bullet[current - 2].classList.remove("active");
      current -= 1;
    };

    const submit = () => {
      const bullet = document.querySelectorAll(".step .bullet");

      bullet[current - 1].classList.add("active");
      current += 1;
      setTimeout(() => {
        alert("Successfully submited");
        location.reload();
      }, 3000);
    };

    return {
      firstNextBtn,
      prevBtnSec,
      nextBtnSec,
      prevBtnThird,
      nextBtnThird,
      prevBtnFourth,
      submit,
    };
  },
};
</script>

<style>
</style>