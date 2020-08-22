<template>
  <div class="home">
    <CustomText class="a1">Selam</CustomText>
    <CustomText tag="p">Selam</CustomText>
    <CustomText tag="p" size="xsmall">Selam</CustomText>
    <IconHome />
  </div>
</template>

<script>
import CustomText from "@/components/CustomText";
import IconHome from "../icons/home.svg";
export default {
  name: "Home",
  components: {
    CustomText,
    IconHome
  }
};
</script>

<style>
.a1 {
  color: rgb(var(--a72));
}
.a2 {
  color: rgb(var(--b3f));
}
.a3 {
  color: rgb(var(--ba8));
}
</style>