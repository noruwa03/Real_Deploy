<template>
  <div>
    <a class="logo-image" href="">
      <img src="@/assets/images/logo.svg" alt="logo" />
    </a>

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
        <a class="navbar-brand logo-image" href="">
          <img src="@/assets/images/logo.svg" alt="logo" />
        </a>
        <!-- End of Logo -->

        <ul class="nav-item-list">
          <li class="nav-item"><a class="nav-link" href="">About</a></li>
          <li class="nav-item"><a class="nav-link" href="">Case Study</a></li>
          <li class="nav-item"><a class="nav-link" href="">Services</a></li>
          <li class="nav-item"><a class="nav-link" href="">Jobs</a></li>
          <li class="nav-item"><a class="nav-link" href="">Contact</a></li>
        </ul>

        <div class="get-free-quote">
          <span class="anchor-link" @click="goto"> Get a free quote </span>
 
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

    const goto = () => {
      const el = document.querySelector("#contact");
      el.scrollIntoView(false);
      
    };
    return {
      menuHandler, goto
    }
  },

 
}
</script>

<style>
</style>


   