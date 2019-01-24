<template>
  <div>
    <FeaturesNav />
    <div class="container">
      <nuxt-child />
    </div>
  </div>
</template>

<script>
import FeaturesNav from '~/components/FeaturesNav'

export default {
    name: 'Features',
    components: {
        FeaturesNav
    }
}
</script>

