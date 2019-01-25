<template>
  <nav 
    :class="{'navbar-flex': navToggled}"
    class="landing-navbar navbar-expand-lg navbar-light bg-white">
    <div class="nav-collapsed">
      <nuxt-link 
        class="navbar-brand" 
        to="/"
      >
        <img 
          src="~assets/TraxitHeroLogo.png" 
          class="hero-logo"
        >
      </nuxt-link>
      <div class="align-self-center">
        <button 
          class="btn-toggle" 
          @click="toggleNav">
          <i class="fas fa-bars"></i>
        </button>
      </div>
    </div>


    <div 
      :class="{'responsive': navToggled}"
      class="nav-links align-self-center"
    >
      <ul class="navbar-nav ml-auto text-right">
        <li class="nav-item">
          <a href="#mission">Our Mission</a>
        </li>
        <li class="nav-item">
          <nuxt-link to="/features/overview">Features</nuxt-link>
        </li>
        <li class="nav-item">
          <a href="#pricing">Pricing</a>
        </li>
        <li class="nav-item">
          <a href="#contact">Contact</a>
        </li>
        <li class="nav-item">
          <nuxt-link to="/support">Support</nuxt-link>
        </li>
        <li 
          :class="{'login-btn': navToggled == false}" 
          class="nav-item"
        >
          <nuxt-link to="/login">Login</nuxt-link>
        </li>
      </ul>
    </div>
  </nav>
</template>

<script>
export default {
    name: 'LandingNav',
    data() {
      return {
        navToggled: false
      }
    },
    methods: {
      toggleNav() {
        this.navToggled = !this.navToggled
      }
    }
}
</script>

<style>
.landing-navbar {
  padding: 10px 25px;
  display: flex;
  justify-content: space-between;
}

.btn-toggle {
  display: none;
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

.nav-links {
  margin-left: auto!important;
}
 

@media only screen and (max-width: 1000px){
  .landing-navbar {
    padding: 0 !important;
  }
  .navbar-flex {
    display: flex;
    flex-direction: column !important;
  }

  .nav-collapsed {
    width: 100%;
    display: flex;
    justify-content: space-between;
    padding: 15px;
  }

  .btn-toggle {
    display: block;
    background: white;
    border-radius: 5px;
    padding: 0 7px;
    border: none;
    font-size: 1.25rem;
  }

    li a {
    text-decoration: none;
    margin-left: 25px;
    letter-spacing: 1px;
    color: var(--gray-color);
    font-weight: 400;
    font-size: 16px !important;
  }

  .nav-links {
    display: none;
    margin-left: 0!important;
  }

  .navbar-nav {
    padding: 10px;
    display: flex!important;
    flex-direction: row;
    justify-content: space-around;
    flex-wrap: wrap!important;
  }

  .responsive {
    display: block;
    transition: 5s heigt ease-in;
  }
}
</style>


