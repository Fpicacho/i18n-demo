<template>
  <div class="home">
    <p>{{ $t("classical.title") }}</p>
    <p>{{ $t("classical.content") }}</p>
  </div>
</template>

<script>
export default {
  name: "Home",
  mounted() {
    console.log(this.$t("classical.title"));
  },
  components: {},
};
</script>
