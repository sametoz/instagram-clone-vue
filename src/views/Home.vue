<template>
  <div class="home">
    <CustomText>Selam</CustomText>
  </div>
</template>

<script>
import CustomText from "@/components/CustomText";
export default {
  name: "Home",
  components: {
    CustomText
  }
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