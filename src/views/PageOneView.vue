<template>
  <h1>New Element</h1>
  <p>this is not mounted, why?</p>
  <p>console.log</p>
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
