<template>
  <div>
    <h2>{{ name }}</h2>
    <p>{{ message }}</p>
  </div>
</template>
 
<script>
export default {
  data() {
    return {
      name: 'Burger, Pizza, Sandwhich',
      message: 'I like burgers, pizzas and sandwhiches'
    }
  }
};
</script>
 
<style></style>