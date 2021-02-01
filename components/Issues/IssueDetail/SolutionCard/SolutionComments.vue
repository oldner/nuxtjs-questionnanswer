<template>
  <div class="solution-card-comments">
    <div class="solution-comments">
      <vs-card id="solution-comments">
        <template #text>
          <div class="solution-comment-field">
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
    document.querySelector("#solution-comments").style.height = `${
      document.querySelector("#solution-card").offsetHeight
    }px`;
  },
};
</script>

<style>
.solution-card-comments {
  height: 100%;
}

.solution-comments {
  position: absolute;
  width: 27%;
  z-index: 1;
  height: 100%;
  right: 30px;
}

.solution-comments .vs-card {
  background-color: #b7d3b8;
  width: 100%;
  height: 100%;
  padding: 10px 0;
  padding-left: 20px;
  overflow-y: auto;
}

.user-comment .vs-card {
  background-color: #f3f3f3;
  width: 97%;
  margin-left: 10px;
}

.solution-comment-field {
  display: flex;
  justify-content: flex-start;
  margin-bottom: 10px;
}
</style>