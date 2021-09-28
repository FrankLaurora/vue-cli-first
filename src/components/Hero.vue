<template>
  <div class="container">
      <img src="https://italiancoders.it/wp-content/uploads/2018/01/vuejs-spotlight.png" alt="spotlight on Vue">
      <h2>...non è un gran ché.</h2>
  </div>
</template>

<script>
export default {
    name: 'Hero'
}
</script>

<style scoped>
    .container {
        position: relative;
    }
    img {
        width: 100%;
    }

    h2 {
        position: absolute;
        right: 20px;
        bottom: 20px;
        color: aquamarine;
    }
</style>