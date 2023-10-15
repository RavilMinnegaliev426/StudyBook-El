<script>
import { Search } from "@opentiny/vue";
import ProgressBar from "./components/progressBar.vue";
import Seacher from "./components/Seacher.vue";
export default {
  components: {
    ProgressBar,
    Seacher,
  },
  data() {
    return {
      greeting: "Hello from parent",
    };
  },
  components: {
    ProgressBar,
    Search,
  },
};
</script>

<template>
  <div class="Global-wrapper">
    <h1>Hi</h1>
    <ProgressBar />
    <Search />
  </div>
</template>

<style>
.Global-wrapper {
  max-width: 300px;
}
</style>
