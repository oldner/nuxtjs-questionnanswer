<template>
  <div class="issue-detail-card-comments">
    <div class="issue-detail-comments">
      <vs-card id="comment-card">
        <template #text>
          <div class="issue-detail-comment-field">
            <div class="user-avatar">
              <vs-avatar circle>
                <template #text> Joel </template>
              </vs-avatar>
            </div>
            <div class="user-comment">
              <vs-card>
                <template #text>
                  <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit.
                    Recusandae molestias, totam sapiente nemo consequatur
                    consectetur vel tempora, maiores suscipit aspernatur,
                    dolorum perferendis minima eos repudiandae.
                  </p>
                </template>
              </vs-card>
            </div>
          </div>
        </template>
      </vs-card>
    </div>
  </div>
</template>

<script>
export default {
  mounted() {
    document.querySelector("#comment-card").style.height = `${
      document.querySelector("#issue-detail-card").offsetHeight
    }px`;
  },
};
</script>

<style>
.issue-detail-comments {
  position: absolute;
  width: 27%;
  z-index: 1;
  right: 30px;
}

.issue-detail-comments .vs-card {
  background-color: #fc9191;
  width: 100%;
  padding: 10px 0;
  padding-left: 20px;
  overflow-y: auto;
  height: 100%;
}

.user-comment .vs-card {
  background-color: #f3f3f3;
  width: 97%;
  margin-left: 10px;
}

.issue-detail-comment-field {
  display: flex;
  justify-content: flex-start;
  margin-bottom: 10px;
}
</style>