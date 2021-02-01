<template>
  <div class="issue-main">
    <div class="navbar-issues"></div>
    <div class="issue-detail-wrapper">
      <issue-detail-card></issue-detail-card>
      <solution-card></solution-card>
      <solution-card></solution-card>
      <solution-card></solution-card>
    </div>
  </div>
</template>

<script>
import IssueDetailCard from "@/components/Issues/IssueDetail/IssueCard/IssueDetailCard.vue";
import SolutionCard from "@/components/Issues/IssueDetail/SolutionCard/SolutionCard.vue";
export default {
  components: {
    IssueDetailCard,
    SolutionCard,
  },
};
</script>

<style>
.issue-main {
  background-color: #e5eae3;
  width: 100%;
  font-family: "Dosis";
}

.navbar-issues {
  width: 100%;
  height: 50px;
  background-color: rgb(250, 206, 206);
}

.issue-detail-wrapper {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}
</style>