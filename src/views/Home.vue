<template>
  <div class="home">
    <CustomText>Selam</CustomText>
    <CustomText tag="p">Selam</CustomText>
    <CustomText tag="b" size="xsmall">Selam</CustomText>
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