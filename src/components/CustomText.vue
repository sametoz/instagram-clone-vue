<template>
  <component :is="tag" :class="size">
    <slot />
  </component>
</template>

<script>
export default {
  name: "CustomText",
  props: {
    tag: {
      type: String,
      default: "span",
      validator: function(value) {
        return ["normal", "small", "xsmall", "xxsmall"].indexOf(value) !== -1;
      }
    },
    size: {
      default: "normal" // normal: 14, small: 12, xsmall: 11, xxsmall: 10
    }
  }
};
</script>

<style scoped>
.normal {
  font-size: 14px;
}
.small {
  font-size: 12px;
}
.xsmall {
  font-size: 11px;
}
.xxsmall {
  font-size: 10px;
}
</style>