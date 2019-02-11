<template>
  <div>
    <FeaturesNav class="sticky-top" />
    <div class="container p-0">
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

