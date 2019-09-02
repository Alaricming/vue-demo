<template>
  <div>
    <p>{{name}}</p>
    <p>{{age}}</p>
  </div>
</template>
<script>
export default {
  name: "Test",
  props: ["age"],
  data() {
    return {
      name: "haha"
    };
  }
};
</script>
<style scoped>
</style>