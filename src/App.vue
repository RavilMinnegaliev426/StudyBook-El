<script>
import ProgressBar from "./components/progressBar.vue";
export default {
  components: {
    ProgressBar,
  },
  data() {
    return {
      greeting: "Hello from parent",
    };
  },
  components: {
    ProgressBar,
  },
};
</script>

<template>
  <h1>Hi</h1>
  <ProgressBar />
</template>
