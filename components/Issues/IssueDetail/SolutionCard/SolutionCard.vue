<template>
  <div class="solution-main">
    <solution-icon class="solution-card-icons"></solution-icon>
    <solution-content class="solution-card-content"></solution-content>
    <solution-comments class="solution-card-comments"></solution-comments>
  </div>
</template>

<script>
import SolutionIcon from "./SolutionIcon";
import SolutionComments from "./SolutionComments.vue";
import SolutionContent from "./SolutionContent.vue";

export default {
  components: {
    SolutionIcon,
    SolutionComments,
    SolutionContent,
  },
};
</script>

<style>
.solution-main {
  display: flex;
  justify-content: center;
  padding: 50px 0px;
  margin: 0;
  width: 90%;
  position: relative;
}

.solution-card-icons {
  width: 5%;
}

.solution-card-content {
  width: 68%;
  z-index: 2;
}

.solution-card-comments {
  width: 27%;
  z-index: 1;
}
</style>