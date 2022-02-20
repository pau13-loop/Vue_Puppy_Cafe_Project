<template>
  <div class="homecontent">
    <div class="content-first-card">
      <FirstCardHomeContent />
    </div>
    <div>
      <p>a</p>
      <p>a</p>
      <p>a</p>
      <p>a</p>
      <p>a</p>
      <p>a</p>
      <p>a</p>
      <p>a</p>
      <p>a</p>
      <p>a</p>
      <p>a</p>
      <p>a</p>
      <p>a</p>
      <p>a</p>
      <p>a</p>
      <p>a</p>
      <p>a</p>
      <p>a</p>
      <p>a</p>
      <p>a</p>
      <p>a</p>
      <p>a</p>
      <p>a</p>
      <p>a</p>
      <p>a</p>
      <p>a</p>
      <p>a</p>
      <p>a</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "HomeContent",
  components: {
    FirstCardHomeContent: () =>
      import("@/components/home/content/FirstCardHomeContent.vue"),
  },
};
</script>

<style>
.content-first-card {
  margin-top: 50px;
}
</style>
