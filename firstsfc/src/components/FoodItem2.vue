<template>
  <div class = "fisch">
    <h2>{{ name }}</h2>
    <p>{{ message }}</p>
  </div>
</template>
 
<script>
export default {
  data() {
    return {
      name: 'Salmon, Tuna, Tilapia',
      message: 'I like fisch'
    }
  }
};
</script>
 
<style>
   .fisch {
    border: dashed black 1px;
    display: inline-block;
    margin: 10px;
    padding: 10px;
    background-color: lightblue;
  }
</style>