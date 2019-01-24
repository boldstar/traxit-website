<template>
  <div>
    <div class="card-body shadow p-4 text-center text-primary h2">
      <span>Overview</span>
      <div>
        <i class="fas fa-table"></i>
      </div>
    </div>
    <div class="p-3 d-flex flex-column bg-light mt-2">
      <div class="card-body bg-white shadow-sm">
        <h3>Workflows</h3>
        <nuxt-link 
          to="/features/workflows"
          class="btn btn-outline-primary btn-sm"
        >
          View
        </nuxt-link>
      </div>
      <div class="card-body bg-white shadow-sm">
        <h3>Engagements</h3>
        <nuxt-link 
          to="/features/engagements"
          class="btn btn-outline-primary btn-sm"
        >
          View
        </nuxt-link>
      </div>
      <div class="card-body bg-white shadow-sm">
        <h3>Tasks</h3>
        <nuxt-link 
          to="/features/tasks"
          class="btn btn-outline-primary btn-sm"
        >
          View
        </nuxt-link>
      </div>
      <div class="card-body bg-white shadow-sm">
        <h3>Dashboard</h3>
        <nuxt-link 
          to="/features/dashboard"
          class="btn btn-outline-primary btn-sm"
        >
          View
        </nuxt-link>
      </div>
      <div class="card-body bg-white shadow-sm">
        <h3>Reports</h3>
        <nuxt-link 
          to="/features/reports"
          class="btn btn-outline-primary btn-sm"
        >
          View
        </nuxt-link>
      </div>
      <div class="card-body bg-white shadow-sm">
        <h3>Management</h3>
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

.card-body {
  display: flex;
  justify-content: space-between;
}

.card-body:hover {
cursor: pointer;
background-color: #70707011 !important;
}

.card-body:nth-child(even) {
  margin: 15px 0;
}

</style>


