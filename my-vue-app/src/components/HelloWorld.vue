<template>
  <div class="greeting-box">
    <h2>{{ greeting }}</h2>
    <p>Welcome to Vue single-file components!</p>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  data() {
    return {
      greeting: "Hello from the Template!"
    };
  }
};
</script>

<style scoped>
.greeting-box {
  padding: 5rem;
  border: 2px solid #4f46e5;
  border-radius: 8px;
  text-align: center;
  color: #f7f7f7;
}
</style>
