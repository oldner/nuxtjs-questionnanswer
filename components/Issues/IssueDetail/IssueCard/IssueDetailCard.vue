<template>
  <div class="issue-detail-main">
    <issue-detail-icon class="issue-detail-card-icons"></issue-detail-icon>
    <issue-detail-content
      class="issue-detail-card-content"
    ></issue-detail-content>
    <issue-detail-comments
      class="issue-detail-card-comments"
    ></issue-detail-comments>
  </div>
</template>

<script>
import IssueDetailIcon from "./IssueDetailIcon";
import IssueDetailComments from "./IssueDetailComments.vue";
import IssueDetailContent from "./IssueDetailContent.vue";

export default {
  components: {
    IssueDetailIcon,
    IssueDetailComments,
    IssueDetailContent,
  },
};
</script>

<style>
.issue-detail-main {
  display: flex;
  justify-content: center;
  padding: 50px 0px;
  margin: 0;
  width: 90%;
  position: relative;
}

.issue-detail-card-icons {
  width: 5%;
}

.issue-detail-card-content {
  width: 68%;
  z-index: 2;
}

.issue-detail-card-comments {
  width: 27%;
  z-index: 1;
  height: 100%;
}
</style>