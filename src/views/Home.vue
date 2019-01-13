<template>
  <div class="home-view">
    <div class="container mx-auto grid-container">
      <house-card
        v-for="(i, index) in 50"
        :key="index"></house-card>
    </div>
  </div>
</template>

<script>
import HouseCard from '@/components/HouseCard.vue';

export default {
  name: 'Home',
  components: {
    HouseCard,
  },
};
</script>
