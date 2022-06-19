<template>
  <newComp />
</template>

<script>
// @ is an alias to /src
import newComp from "@/components/newComp.vue";

export default {
  name: "pageOne",
  components: {
    newComp,
  },
};
</script>

<style scoped>
h1 {
  color: blue;
}
</style>
