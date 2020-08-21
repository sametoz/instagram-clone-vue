<template>
  <div class="home">Test Sayfası</div>
</template>

<script>
export default {
  name: "Home"
};
</script>

<style>
h1 {
  color: red;
  @media (--t) {
    color: blue;
  }
}
</style>