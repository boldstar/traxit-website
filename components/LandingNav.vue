<template>
  <b-navbar 
    toggleable="md" 
    type="dark" 
    variant="primary">
    <div class="container">

      <b-navbar-brand to="/">TRAXIT</b-navbar-brand>

      <b-navbar-toggle target="feature_nav_collapse"></b-navbar-toggle>

      <b-collapse 
        id="feature_nav_collapse"
        is-nav 
      >

        <!-- Right aligned nav items -->
        <b-navbar-nav class="ml-auto">
          <b-nav-item to="/features/overview">Overview</b-nav-item>
          <b-nav-item to="/features/workflows">Workflows</b-nav-item>
          <b-nav-item to="/features/engagements">Engagements</b-nav-item>
          <b-nav-item to="/features/tasks">Tasks</b-nav-item>
          <b-nav-item to="/features/dashboard">Dashboard</b-nav-item>
          <b-nav-item to="/features/reports">Reports</b-nav-item>
          <b-nav-item to="/features/manage">Manage</b-nav-item>
        </b-navbar-nav>

      </b-collapse>
    </div>
  </b-navbar>
</template>

<script>
export default {
    name: 'LandingNav',
    methods: {
      changeDisplay() {
        console.log(this.$refs.toggle)
      }
    }
}
</script>

<style>
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


