<template>
  <div v-for="post of contents" v-bind:key="post.id">
    <h3>{{ post.title }}</h3>
    <p>{{ post.date }}</p>
  </div>
</template>

<script>
export default {
  name: "list",
  props: {
    contents: Array,
  },
};
</script>

<style></style>
