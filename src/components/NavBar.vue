<template>
    <div class="nav navSticky navDesktop">
        <!-- Navbar Left  start-->
        <div class="mp8"> 
            <a href="">
                <img class="h32px" src="../assets/logoWithFooterBgText2.png" alt="Logo"> 
            </a>
        </div>
        <!-- Navbar Left end -->
        
        <!-- Navbar Center start -->
        <div class="rf">
            <a href="#about" class="navLink mp8">ABOUT</a>
            <a href="#prizes" class="navLink mp8">PRIZES</a>
            <a href="#timeline" class="navLink mp8">TIMELINE</a>
            <a href="#sponsors" class="navLink mp8">SPONSORS</a>
            <!-- <a href="#faqs" class="navLink mp8">FAQs</a> -->
            <a href="#contactus" class="navLink mp8">CONTACT US</a>
        </div>
        <!-- Navbar Center end -->
        
        
        <!-- Navbar Right start -->
        <!-- <div class="mp8">
            <a href="#" target="_blank">
                <img class="logoSize" src="" alt="">
            </a>
        </div> -->
        <!-- Navbar Right end -->
    </div>

<!-- ------------------------------------------------------------------------------- -->    
    <!-- Styling navbar for mobile  start-->
    
    <div class="navMobile navSticky zFix">
        <div class="nav">
        
        <!-- Navbar Hamburger start -->
        <!-- Trying hamburger library -->
            
        <!-- Navbar Left  start-->
        <div class="mp8"> 
            <a href="/">
                <img class="h32px" src="../assets/logo.png" alt="Logo"> 
            </a>
        </div>
        <!-- Navbar Hamburger end -->
        <div class="mp8">
             <!-- Navbar Left end -->
            <Menu right :closeOnNavigation="true" >
                <a href="#about" class="navLink mp8">ABOUT</a>
                <a href="#prizes" class="navLink mp8">PRIZES</a>
                <a href="#timeline" class="navLink mp8">TIMELINE</a>
                    <a href="#sponsors" class="navLink mp8">SPONSORS</a>
                    <!-- <a href="#faqs" class="navLink mp8">FAQs</a> -->
                    <a href="#contactus" class="navLink mp8">CONTACT US</a>
                </Menu>

                   
        </div>

    </div>
    
   <!-- ---------- -->
    </div>
    <!-- Styling navbar for mobile  end-->
    
    
    


</template>

<script>

// import the CSS transitions you wish to use, in this case we are using `
import {  Menu } from 'vue3-burger-menu';  

export default {
    components: {
        // Register your component
        Menu
    },
    setup () {
        
    }
}
</script>

<style>
.navDesktop{
    /* box-shadow: 0px 0px 4px 1px var(--blueDark); */
}
.logoSize{
    height: 32px;
}

/* Trying the hamburger menu 16Dec2022 */

/* Styles from https://www.npmjs.com/package/vue3-burger-menu */

.bm-burger-button {
      position: relative !important;
      width: 24px !important;
      height: 24px !important;
      left: 2px !important;
      /* left: 240px !important; */
      top: 0px !important;
      cursor: pointer;

    }
    .bm-burger-bars {
      background-color: var(--footerBg) !important;
    }
    .line-style {
      position: absolute;
      height: 2px !important;
      left: 0 !important;
      right: 0;
    }
    .cross-style {
      position: absolute;
      top: 12px;
      right: 2px;
      cursor: pointer;
    }
    .bm-cross {
      background: #ffffff !important;
    }
    .bm-cross-button {
      height: 24px;
      width: 24px;
    }
    .bm-menu {
      height: 100%; /* 100% Full-height */
      width: 0; /* 0 width - change this with JavaScript */
      position: fixed; /* Stay in place */
      z-index: 1000; /* Stay on top */
      top: 0;
      left: 0;
      background-color: var(--footerBg) !important; 
      overflow-x: hidden; /* Disable horizontal scroll */
      padding-top: 60px; /* Place content 60px from the top */
      transition: 0.5s; /*0.5 second transition effect to slide in the sidenav*/
    }

    .bm-overlay {
      /* background: rgba(0, 0, 0, 0.3); */
    }
    .bm-item-list {
      color: #ffffff !important;
      margin-left: 10%;
      font-size: 20px;
    }
    .bm-item-list > * {
      display: flex;
      text-decoration: none;
      padding: 0.7em;
    }
    .bm-item-list > * > span {
      margin-left: 10px;
      font-weight: 700;
      color: white !important;
    }
/* Styles for hamburger end*/


/* Styling navbar for mobile */
@media (min-width: 560px){
    .navMobile{
        display: none !important;
    }

}
@media (max-width: 560px){
    .navDesktop{
        display: none !important;
    }
    .navClick{
        display:flex;
        justify-content:center;
        align-items:center;
        position: absolute;
        top:72px;
        left: 104px;
        width: 100%;
        height: 88vh;
        background-color: var(--logoPri) !important;
        color: #fff;
    }
    .zFix{
        z-index: 1000 !important;
    }
    .disNone{
        display: none !important;
    }
}


.h32px{
    height: 32px;
}
.navLink:hover{
    color: var(--logoPri);
}
.navSticky{
    position: sticky;
    top:0;
}
.nav{
    background-color: #fff;
    z-index: 8;
}
</style>