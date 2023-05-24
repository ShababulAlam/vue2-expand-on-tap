<template>
  <div>
    <div>Expandable {{ text }}</div>
  </div>
</template>

<script>
export default {
  name: "ExpandOnTap",
  props: {
    text: {
      type: String,
      default: "",
    },
  },
};
</script>

<style lang="scss" scoped></style>
