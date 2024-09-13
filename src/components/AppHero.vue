<template>
  <div class="jumbotron">
    <h2>{{ subtitle }}</h2>
    <p class="main">Qui mostri quello che contiene il jumbotron</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      subtitle: "Questo è un jumbotron"
    };
  }
};
</script>

<style scoped>
.jumbotron {
  padding: 2rem;
  background-color: #f8f9fa;
  border-radius: 0.3rem;
  text-align: center;
}
.main {
  font-size: 1.25rem;
  font-weight: 300;
}
</style>
