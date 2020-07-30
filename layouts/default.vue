<template>
  <div class="main">
    <navigation></navigation>
    <nuxt />
    <bottomNavigation></bottomNavigation>
  </div>
</template>

<script>
import navigation from '~/components/Navigation.vue';
import bottomNavigation from '~/components/BottomNavigation.vue';

export default {
  components: {
    bottomNavigation,
    navigation
  }
};
</script>
