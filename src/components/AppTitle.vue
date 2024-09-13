<template>
  <h1>{{ title }}</h1>
</template>

<script>
export default {
  data() {
    return {
      title: "Welcome to My Vue App"
    };
  }
};
</script>

<style scoped>
h1 {
  font-size: 2.5rem;
  text-align: center;
  color: #333;
}
</style>
