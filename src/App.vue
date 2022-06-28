<template>
  <div>
    <h2>Vue-log</h2>
    <List :contents="posts" />
  </div>
</template>

<script>
import List from "./components/List.vue";
import posts from "./assets/posts.js";

export default {
  name: "App",

  components: {
    List,
  },

  data() {
    return { posts: posts };
  },
};
</script>
