<template>
  <div class = "junk">
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

<style>
   .junk {
    border: dashed black 1px;
    display: inline-block;
    margin: 10px;
    padding: 10px;
    background-color: lightgreen;
  }
</style>