<template>
  <div class="main">
    <navigation></navigation>
    <nuxt />
  </div>
</template>

<script>
import navigation from '~/components/Navigation.vue'

export default {
  components: {
    navigation
  }
}
</script>
