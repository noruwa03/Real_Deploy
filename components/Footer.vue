<template>
  <footer>
    <!-- <div class="container-lg">
      <div class="row align-items-start justify-content-between">
        <div class="col-lg-5 col-12">
          <div class="row align-items-center justify-content-between">
            <div class="col-12">
              <div class="brand-name">Ecolabz</div>
            </div>
            <div class="col-12 about my-3">
              Your trusted partner in building sustainable products for the future. Be it blockchain development, AI, web apps, UI/UX design or SaaS. We are on a mission to give your startup a headstart.
            </div>
            <div class="col-12 mt-2 mb-5">
              <a href="" class="me-3">
                <img src="@/assets/icons/discord.svg" alt="Discord">
              </a>
              <a href="" class="me-3">
                <img src="@/assets/icons/instagram.svg" alt="Instagram">
              </a>
              <a href="" class="me-3">
                <img src="@/assets/icons/meta.svg" alt="Meta">
              </a>
              <a href="">
                <img src="@/assets/icons/twitter.svg" alt="Twitter">
              </a>
            </div>
          </div>
        </div>
        <div class="col-lg-7 col-12">
          <div
            class="
              row
              align-items-center
              justify-content-between justify-content-sm-center
            "
          >
            <div class="col-lg-4 col-sm-4 col-6 my-3 footer-anchor-link">
              <h5>Explore</h5>         
              <a href="">What we do</a>
              <a href="">Creative Markets</a>
              <a href="">Careers</a>
              <a href="">Press</a>
            </div>
            <div class="col-lg-4 col-sm-4 col-6 my-3 footer-anchor-link">
              <h5>About</h5>
              <a href="">Community</a>
              <a href="">Designers</a>
              <a href="">Support</a>
              <a href="">Terms of Services</a>
            </div>
            <div class="col-lg-4 col-sm-4 col-6 my-3 footer-anchor-link">
              <h5>More</h5>
              <a href="">Tag</a>
              <a href="">API</a>
              <a href="">Privacy Policy</a> 
              <a href="">Blog</a>                    
            </div>
          </div>
        </div>
        
      </div>
    </div> -->

    <div class="container-lg">
    
      <div class="row align-items-center justify-content-between">
        <div class="col-lg-4 col-12 address">
          <h4>Offices</h4>
            <div>
              United States <span> 30 N Gould St R, Sheridan, WY 82801 </span>
            </div>
            <div>
              Nigeria
              <span> 17 Ozo Ocheoha Street Independence Layout Enugu </span>
            </div>

            <div>Tanzania <span> 1 Morogoro Road, Dar Es Salaam </span></div>

            
        </div>

        <div class="col-lg-4 col-12 text-center">
         <div class="footer-logo">
           <img src="@/assets/icons/logo.svg" alt="logo"
        />
         </div>
           <div class="contact-email">
              <!-- <img
                src="@/assets/icons/information.svg"
                class="email-info me-1"
                alt="Information"
              /> -->
              <a href="mailto:contact@ecolabz.io">contact@ecolabz.io</a>
            </div>
          
        </div>

        <div class="col-lg-4 col-12 text-center text-sm-end">
          <div class="row align-items-center justify-content-between">
           
           
            <div class="col-12">
              
              <a href="" class="me-4">
                <img src="@/assets/icons/instagram.svg" alt="Instagram" />
              </a>
             
              <a href="">
                <img src="@/assets/icons/twitter.svg" alt="Twitter" />
              </a>
            </div>
          </div>
        </div>

       
        
      </div>
    </div>
    <div class="all-rights-reserved">
      <p>{{ footerDate }} All Rights Reserved</p>
    </div>
  </footer>
</template>

<script>
export default {
  setup() {
    const footerDate = new Date().getFullYear();
    return { footerDate };
  },
};
</script>

<style>
</style>