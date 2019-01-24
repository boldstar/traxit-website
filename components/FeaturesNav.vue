<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <div class="container">
      <nuxt-link 
        class="navbar-brand font-weight-bold" 
        to="/"
      >
        TRAXIT
      </nuxt-link>
      <button 
        class="navbar-toggler" 
        type="button" 
        data-toggle="collapse" 
        data-target="#navbarSupportedContent" 
        aria-controls="navbarSupportedContent" 
        aria-expanded="false" 
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div 
        id="navbarSupportedContent"
        class="collapse navbar-collapse" 
      >
        <ul class="navbar-nav ml-auto">
          <li class="nav-item">
            <nuxt-link
              :class="{ 'active-link': $route.name == 'features-overview'}" 
              class="nav-link" 
              to="/features/overview"
            >
              Overview
            </nuxt-link>
          </li>
          <li class="nav-item">
            <nuxt-link
              :class="{ 'active-link': $route.name == 'features-workflows'}"
              class="nav-link"  
              to="/features/workflows"
            >
              Workflows
            </nuxt-link>
          </li>
          <li class="nav-item">
            <nuxt-link
              :class="{ 'active-link': $route.name == 'features-engagements'}"
              class="nav-link"  
              to="/features/engagements"
            >
              Engagements
            </nuxt-link>
          </li>
          <li class="nav-item">
            <nuxt-link
              :class="{ 'active-link': $route.name == 'features-tasks'}" 
              class="nav-link" 
              to="/features/tasks"
            >
              Tasks
            </nuxt-link>
          </li>
          <li class="nav-item">
            <nuxt-link
              :class="{ 'active-link': $route.name == 'features-dashboard'}"
              class="nav-link"  
              to="/features/dashboard"
            >
              Dashboard
            </nuxt-link>
          </li>
          <li class="nav-item">
            <nuxt-link
              :class="{ 'active-link': $route.name == 'features-reports'}"
              class="nav-link"  
              to="/features/reports"
            >
              Reports
            </nuxt-link>
          </li>
          <li class="nav-item">
            <nuxt-link
              :class="{ 'active-link': $route.name == 'features-manage'}"
              class="nav-link"  
              to="/features/manage"
            >  
              Manage
            </nuxt-link>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
    name: 'FeaturesNav'
}
</script>

<style>
  .nav-item {
    margin-left: 20px;
  }

  .nav-link {
    font-weight: 500;
  }

  .active-link {
    color: white !important;
    font-size: 1.25rem;
    padding: 0;
    margin-top: 3px;
  }
</style>


