<template>
  <div class="overview bg-light">
    <div class="card-header shadow-sm p-4 text-primary h2 d-flex justify-content-between bg-white">
      <span>Overview</span>
      <div>
        <i class="fas fa-table"></i>
      </div>
    </div>
    <div class="overview-body">
      <div class="card-body features-card-body bg-white shadow-sm d-flex flex-column  justify-content-between">
        <div class="d-flex justify-content-between h3 mb-3">
          <span class="align-self-center">Workflows</span>
          <i class="fas fa-route mr-3 text-primary align-self-center"></i>
        </div>
        <nuxt-link 
          to="/features/workflows"
          class="btn btn-outline-primary btn-sm"
        >
          View
        </nuxt-link>
      </div>
      <div class="card-body features-card-body bg-white shadow-sm d-flex flex-column justify-content-between">
        <div class="d-flex justify-content-between h3 mb-3">
          <span class="align-self-center">Engagements</span>
          <i class="far fa-folder-open mr-3 text-primary align-self-center"></i>
        </div>
        <nuxt-link 
          to="/features/engagements"
          class="btn btn-outline-primary btn-sm"
        >
          View
        </nuxt-link>
      </div>
      <div class="card-body features-card-body bg-white shadow-sm d-flex flex-column justify-content-between">
        <div class="d-flex justify-content-between h3 mb-3">
          <span class="align-self-center">Tasks</span>
          <i class="fas fa-tasks mr-3 text-primary align-self-center"></i>
        </div>
        <nuxt-link 
          to="/features/tasks"
          class="btn btn-outline-primary btn-sm"
        >
          View
        </nuxt-link>
      </div>
      <div class="card-body features-card-body bg-white shadow-sm d-flex flex-column justify-content-between">
        <div class="d-flex justify-content-between h3 mb-3">
          <span class="align-self-center">Dashboard</span>
          <i class="fas fa-tachometer-alt mr-3 text-primary align-self-center"></i>
        </div>
        <nuxt-link 
          to="/features/dashboard"
          class="btn btn-outline-primary btn-sm"
        >
          View
        </nuxt-link>
      </div>
      <div class="card-body features-card-body bg-white shadow-sm d-flex flex-column justify-content-between">
        <div class="d-flex justify-content-between h3 mb-3">
          <span class="align-self-center">Reports</span>
          <i class="fas fa-database mr-3 text-primary align-self-center"></i>
        </div>
        <nuxt-link 
          to="/features/reports"
          class="btn btn-outline-primary btn-sm"
        >
          View
        </nuxt-link>
      </div>
      <div class="card-body features-card-body bg-white shadow-sm d-flex flex-column justify-content-between">
        <div class="d-flex justify-content-between h3 mb-3">
          <span class="align-self-center">Manage</span>
          <i class="fas fa-clipboard mr-3 text-primary align-self-center"></i>
        </div>
        <nuxt-link 
          to="/features/manage"
          class="btn btn-outline-primary btn-sm"
        >
          View
        </nuxt-link>
      </div>
    </div>
  </div>
</template>

<script>
export default {
    name: 'Overview'
}
</script>

<style>
.overview {
  min-height: 100vh;
  display: flex;
  flex-direction: column;
}

.overview-body {
  display: flex;
  justify-content: space-around;
  flex-wrap: wrap;
  width: 100%;
  margin: 5vh 0;
}

.features-card-body {
  width: 20rem;
  margin: 10px;
}

@media screen and (max-width: 600px) {
  .features-card-body {
    margin-bottom: 20px !important;
  }
}

h3 {
  color: #707070 !important;
  margin: 0;
}

.features-card-body:hover {
  cursor: pointer;
  background-color: #70707011 !important;
}


</style>


