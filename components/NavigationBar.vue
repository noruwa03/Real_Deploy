<template>
  <div>
 
    <nuxt-link class="logo-image"  to="/"> <img src="@/assets/images/logo.svg" alt="logo" /></nuxt-link>

    <div id="menu-btn" @click="menuHandler">
      <span></span>
      <span></span>
      <span></span>
      <span></span>
      <span></span>
      <span></span>
    </div>
   

    <!-- Navigation -->
    <nav>
      <div class="nav-item-container">
        <!-- Logo -->
       
        <nuxt-link class="navbar-brand logo-image" to="/"><img src="@/assets/images/logo.svg" alt="logo" /></nuxt-link>
        <!-- End of Logo -->

        <ul class="nav-item-list">
          <li @click="removeSidebar" class="nav-item"><a class="nav-link" href="#about-us" >About</a></li>
          
          <li @click="removeSidebar"  class="nav-item"><a class="nav-link" href="#services">Services</a></li>
          <li class="nav-item"><a class="nav-link" href="">Portfolio</a></li>
          <li class="nav-item"><a class="nav-link" href="">Jobs</a></li>
          <li @click="removeSidebar" class="nav-item">
          <nuxt-link class="nav-link" to="/contact">Contact</nuxt-link>
         
          </li>
        </ul>

        <div class="get-free-quote">
          <a class="anchor-link" href="#contact"> Get a free quote </a>
 
        </div>
      </div>
    </nav>

    <!-- End of Navigation -->
  </div>
</template>


<script>


export default {
  setup() {
    const menuHandler = () => {
      const navIcon2 = document.querySelector("#menu-btn");
      const nav = document.querySelector("nav");
      const navItem = document.querySelector(".nav-item-list");

      nav.classList.toggle("active");
      navItem.classList.toggle("active");
      navIcon2.classList.toggle("open");
    }

    // const goto = () => {
    //   const el = document.querySelector("#contact");
    //   el.scrollIntoView(false);
      
    // };

    const removeSidebar = () => {
      const navIcon2 = document.querySelector("#menu-btn");
      const nav = document.querySelector("nav");
      const navItem = document.querySelector(".nav-item-list");

      nav.classList.toggle("active");
      navItem.classList.toggle("active");
      navIcon2.classList.toggle("open");
      
    };

    

    
    return {
      menuHandler, removeSidebar, 
    }
  },

 
}
</script>

<style>
</style>


   