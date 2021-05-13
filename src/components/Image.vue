<template>
  <img :class="imageStyles" :src="src" :alt="alt" />
</template>
<script>
export default {
  name: "Image",
  props: ["styles", "src", "alt"],
  computed: {
    imageStyles() {
      return this.styles;
    },
  },
};
</script>
