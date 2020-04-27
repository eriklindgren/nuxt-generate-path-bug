<template> </template>

<script>
export default {
  async asyncData() {
    return await new Promise((resolve) => setTimeout(resolve, 500));
  },
};
</script>
