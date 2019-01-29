<template>
  <div>
    <div class="card-body shadow p-4 text-center text-primary h2 d-flex justify-content-between">
      <span>Overview</span>
      <div>
        <i class="fas fa-table"></i>
      </div>
    </div>
    <div class="p-3 d-flex flex-column bg-light mt-2">
      <div class="card-body bg-white shadow-sm d-flex justify-content-between">
        <div>
          <h3><i class="fas fa-route mr-3 text-primary"></i>Workflows</h3>
        </div>
        <nuxt-link 
          to="/features/workflows"
          class="btn btn-outline-primary btn-sm"
        >
          View
        </nuxt-link>
      </div>
      <div class="card-body bg-white shadow-sm d-flex justify-content-between">
        <div>
          <h3><i class="far fa-folder-open mr-3 text-primary"></i>Engagements</h3>
        </div>
        <nuxt-link 
          to="/features/engagements"
          class="btn btn-outline-primary btn-sm"
        >
          View
        </nuxt-link>
      </div>
      <div class="card-body bg-white shadow-sm d-flex justify-content-between">
        <div>
          <h3><i class="fas fa-tasks mr-3 text-primary"></i>Tasks</h3>
        </div>
        <nuxt-link 
          to="/features/tasks"
          class="btn btn-outline-primary btn-sm"
        >
          View
        </nuxt-link>
      </div>
      <div class="card-body bg-white shadow-sm d-flex justify-content-between">
        <div>
          <h3><i class="fas fa-tachometer-alt mr-3 text-primary"></i>Dashboard</h3>
        </div>
        <nuxt-link 
          to="/features/dashboard"
          class="btn btn-outline-primary btn-sm"
        >
          View
        </nuxt-link>
      </div>
      <div class="card-body bg-white shadow-sm d-flex justify-content-between">
        <div>
          <h3><i class="fas fa-database mr-3 text-primary"></i>Reports</h3>
        </div>
        <nuxt-link 
          to="/features/reports"
          class="btn btn-outline-primary btn-sm"
        >
          View
        </nuxt-link>
      </div>
      <div class="card-body bg-white shadow-sm d-flex justify-content-between">
        <div>
          <h3><i class="fas fa-clipboard mr-3 text-primary"></i>Manage</h3>
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

h3 {
  color: #707070 !important;
  margin: 0;
}

.card-body:hover {
cursor: pointer;
background-color: #70707011 !important;
}

.card-body:nth-child(even) {
  margin: 15px 0;
}

</style>


