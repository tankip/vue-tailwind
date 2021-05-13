<template>
  <img class="rounded-lg shadow-xl" :src="image" :alt="alt" />
</template>
<script>
export default {
  name: "Image",
  props: ["image", "alt"]
};
</script>
