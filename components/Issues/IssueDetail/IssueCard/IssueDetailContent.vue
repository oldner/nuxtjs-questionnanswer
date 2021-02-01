<template>
  <div class="issue-detail-card-content">
    <div class="issue-detail">
      <vs-card id="issue-detail-card">
        <template #title>
          <div class="issue-detail-user-info">oldner</div>
        </template>
        <template #text>
          <div class="issue-detail-content">
            <h3>
              Lorem ipsum dolor sit amet consectetur adipisicing elit.
              Molestiae, ea?
            </h3>
            <img
              src="https://media.sproutsocial.com/uploads/2017/02/10x-featured-social-media-image-size.png"
              width="200px"
              alt=""
            />
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Sint
              ullam illum dicta magni voluptatem ea dolorem non quam
              consequuntur, pariatur quisquam quo cumque labore odio, nulla est
              quis praesentium nostrum eaque aspernatur sequi fugiat eveniet
              reprehenderit inventore! Magni quae excepturi corrupti ullam
              aspernatur neque similique harum alias, sed repellendus expedita,
              soluta iusto odio ad blanditiis mollitia quo. Ex, ipsum. Nam
              minus, repellat aspernatur voluptate saepe dolorum corrupti enim
              at incidunt laborum delectus tenetur minima dolor similique
              aperiam, quo maxime sed.
            </p>
            <div class="issue-detail-tags">
              <span>hirsizlik</span>
              <span>yolsuzluk</span>
              <span>kadin-cinayeti</span>
            </div>
          </div>
        </template>
      </vs-card>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.issue-detail-card-content {
  width: 100%;
}

.issue-detail {
  width: 100%;
  z-index: 2;
}

.issue-detail .vs-card {
  min-width: 100% !important;
  background-color: #f05e5e;
  color: #f3f3f3;
}

.issue-detail-user-info {
  padding: 10px 5px;
  font-size: 12pt;
}

.issue-detail-content {
  padding: 10px 5px;
  font-size: 12pt;
}

.issue-detail-content h3 {
  margin-bottom: 20px;
}

.issue-detail-tags {
  margin-top: 50px;
  margin-bottom: 20px;
}
</style>