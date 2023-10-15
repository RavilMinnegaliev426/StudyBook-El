<template>
  <div>
    <tiny-search v-model="value" placeholder="You input"></tiny-search>
    {{ value }}
  </div>
</template>

<script lang="jsx">
import { Search } from "@opentiny/vue";

export default {
  components: {
    TinySearch: Search,
  },
  data() {
    return {
      value: "",
    };
  },
};
</script>
