<template>
  <div class="issue-detail-card-icons">
    <div class="issue-detail-icons">
      <vs-button class="btn-chat" shadow primary>
        <fa :icon="['fas', 'arrow-up']" />
      </vs-button>
      <vs-button class="btn-chat" shadow primary>
        <span class="span"><h2>54</h2></span>
      </vs-button>
      <vs-button class="btn-chat" shadow primary>
        <fa :icon="['fas', 'arrow-down']" />
      </vs-button>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.issue-detail-icons .vs-button {
  width: 50px !important;
  height: 40px !important;
  font-family: "Dosis";
}
.issue-detail-icons .vs-button:first-child {
  background-color: #cf0707;
  color: #f3f3f3;
}

.issue-detail-icons .vs-button:last-child {
  background-color: #aabbe4;
  color: #f3f3f3;
}
</style>