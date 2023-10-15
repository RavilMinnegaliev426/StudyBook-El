<template>
  <div>
    <div class="wrapper-container">
      <div class="wrapper-container-p">
        <p class="p-text">JS</p>
        <div class="wrapper">
          <tiny-progress
            :percentage="value1"
            :show-text="false"
            color="#FEF102"
          ></tiny-progress>
        </div>
      </div>

      <div class="wrapper-container-p">
        <p class="p-text">TS</p>
        <div class="wrapper">
          <tiny-progress
            :percentage="value2"
            :show-text="false"
            color="#23429D"
          ></tiny-progress>
        </div>
      </div>
      <div class="wrapper-container-p">
        <p class="p-text">FT</p>
        <div class="wrapper">
          <tiny-progress
            :percentage="value3"
            :show-text="false"
            color="#EF1D26"
          ></tiny-progress>
        </div>
      </div>
      <div class="wrapper-container-p">
        <p class="p-text">Vue</p>
        <div class="wrapper">
          <tiny-progress
            :percentage="value4"
            :show-text="false"
            color="#03A762"
          ></tiny-progress>
        </div>
      </div>
    </div>
  </div>
</template>
<script lang="jsx">
import { Progress, Button } from "@opentiny/vue";

export default {
  components: {
    TinyProgress: Progress,
    TinyButton: Button,
  },
  data() {
    return {
      value1: 100,
      value2: 75,
      value3: 10,
      value4: 25,
    };
  },
};
</script>

<style>
.wrapper {
  width: 200px;
}
.wrapper-container-p {
  display: flex;
  align-items: center;
  max-height: 20px;
}
.wrapper-container {
}
.p-text {
  width: 30px;
}
</style>
