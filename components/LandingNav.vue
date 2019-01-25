<template>
  <b-navbar 
    toggleable="md" 
    type="light" 
    variant="white">
    <div class="container">
      <b-navbar-brand href="#">
        <img 
          class="hero-logo"
          src="~assets/TraxitHeroLogo.png"
        >
      </b-navbar-brand>
      <b-navbar-toggle target="nav_collapse"></b-navbar-toggle>
      <b-collapse 
        id="nav_collapse"
        is-nav 
      >
        <b-navbar-nav class="ml-auto">
          <b-nav-item href="#mission">Our Mission</b-nav-item>
          <b-nav-item to="/features/overview">Features</b-nav-item>
          <b-nav-item href="#pricing">Pricing</b-nav-item>
          <b-nav-item href="#contact">Contact</b-nav-item>
          <b-nav-item to="/support">Support</b-nav-item>
          <b-nav-item 
            class="login-btn"
            to="/login"
          >
            Login
          </b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </div>
  </b-navbar>
</template>

<script>
export default {
    name: 'LandingNav'
}
</script>

<style>
.navbar-container {
  width: 100%;
}

nav {
  padding: 10px 50px !important;
}

li a {
  text-decoration: none;
  margin-left: 25px;
  letter-spacing: 2px;
  color: var(--gray-color);
  font-weight: 600;
}

li a:hover {
  color: var(--blue-color);
  text-decoration: none;
}

.login-btn a {
  color: var(--pink-color) !important;
  border: 3px solid var(--blue-color)!important;
  border-radius: 10px !important;
  padding: 8px 25px !important;
  font-weight: 600 !important;
}

.login-btn a:hover {
  background-color: var(--blue-color);
  color: white !important;
}
 

@media only screen and (max-width: 1000px){
    li a {
    text-decoration: none;
    margin-left: 25px;
    letter-spacing: 1px;
    color: var(--gray-color);
    font-weight: 400;
    font-size: 12px;
  }
}
</style>


