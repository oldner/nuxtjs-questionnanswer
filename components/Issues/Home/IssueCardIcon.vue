<template>
  <div>
    <div class="issue-card-template">
      <div class="issue-card-icons">
        <vs-button danger icon>
          <fa :icon="['far', 'heart']" />
        </vs-button>
        <vs-button class="btn-chat" shadow primary>
          <fa :icon="['far', 'eye']" />
          <span class="span"> 54 </span>
        </vs-button>
        <vs-button class="btn-chat" shadow primary>
          <fa :icon="['fas', 'arrow-up']" />
          <span class="span"> 54 </span>
        </vs-button>
        <vs-button class="btn-chat" shadow primary>
          <fa :icon="['fas', 'check']" />
          <span class="span"> 54 </span>
        </vs-button>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.issue-card-template .vs-button:first-child {
  display: inline-block;
  transition: all 0.8s ease;
}

.issue-card-template .vs-button:not(:first-child) {
  display: inline-block;
  transition: all 0.8s ease;
  width: 60px;
}

.issue-card-template .vs-button:not(:first-child) span {
  margin-left: 5px;
}
</style>