<template>
  <router-link class="py-2 rounded-md text-center" :to="to">{{ name }} <span v-if="extra" class="uppercase text-xs text-indigo-500">| {{ extra }}</span></router-link>
</template>

<script>
export default {
  name: "Link",
  props: ["to", "name", "extra"],
};
</script>
