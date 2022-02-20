<template>
  <div class="home">
    <HomeContent />
  </div>
</template>

<script>
export default {
  name: "Home",
  components: {
    // @ is an alias to /src
    HomeContent: () => import("@/components/home/HomeContent.vue"),
  },
};
</script>
