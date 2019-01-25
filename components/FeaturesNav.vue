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
    name: 'FeaturesNav'
}
</script>

<style>

.nav-link {
  margin-left: 5px !important;
  font-size: 12px !important;
}
 
</style>


