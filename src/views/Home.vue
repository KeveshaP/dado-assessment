<template>
  <div class="home">
    <Assessment />
  </div>
</template>

<script>
// @ is an alias to /src
import Assessment from '@/components/Assessment.vue';

export default {
  name: "home",
  components: {
    Assessment
  },
};
</script>
