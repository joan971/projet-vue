<template>
<div>
    <b-navbar class="header" toggleable="lg" type="black" variant="white">
        <b-navbar-brand href="#">
            <img src="img/brand/LOGO JAUNE.png" style="width:80px; height:80px;" alt="Mon site">
        </b-navbar-brand>

        <b-navbar-toggle  style="color:black;" target="nav-collapse">☰</b-navbar-toggle>

        <b-collapse id="nav-collapse" is-nav>
            <b-navbar-nav>
                <b-nav-item><router-link to="/">ACCUEIL</router-link></b-nav-item>
                <b-nav-item><router-link to="#">ACTIVITÉS</router-link></b-nav-item>
                <b-nav-item><router-link to="#">A LA UNE</router-link></b-nav-item>
                <b-nav-item><router-link to="/contact">CONTACT</router-link></b-nav-item>
            </b-navbar-nav>

            <!-- Right aligned nav items -->
            <div class="col-lg-6 text-lg-center btn-wrapper">
               <a target="_blank" rel="noopener" href="https://github.com"
                       class="btn btn-neutral btn-icon-only btn-github btn-round btn-lg" data-toggle="tooltip"
                       data-original-title="Star on Github">
                        <i class="fa fa-github"></i>
                    </a>
                   
                    <a target="_blank" rel="noopener" href="https://www.facebook.com"
                       class="btn btn-neutral btn-icon-only btn-facebook btn-round btn-lg" data-toggle="tooltip"
                       data-original-title="Like us">
                        <i class="fa fa-facebook-square"></i>
                    </a>
                  
                 
                </div>
        </b-collapse>
    </b-navbar>
</div>   
          
</template>
<script>
import { BNavbar, BNavbarBrand, BNavbarToggle, BNavbarNav } from "bootstrap-vue/esm/components/navbar";
import { BCollapse } from "bootstrap-vue/esm/components/collapse";
import { BNavItem, BNavItemDropdown, BNavForm } from "bootstrap-vue/esm/components/nav";  
import { BDropdownItem } from "bootstrap-vue/esm/components/dropdown";
import { BFormInput } from "bootstrap-vue/esm/components/form-input";
import { BButton } from "bootstrap-vue/esm/components/button";

export default {
  components: {
    BNavbar,
    BNavbarBrand,
    BNavbarToggle,        
    BCollapse,
    BNavbarNav,    
    BNavItem,
    BNavItemDropdown,        
    BDropdownItem,
    BNavForm,
    BFormInput,
    BButton 
  }
};
</script>
<style>
</style>
