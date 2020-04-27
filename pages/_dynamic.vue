<template> </template>

<script>
export default {
  fetch() {
    console.log(this.$nuxt.context.route.path);
  },
};
</script>
