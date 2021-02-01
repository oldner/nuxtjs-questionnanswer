<template>
  <div class="solution-card-content">
    <div class="solution">
      <vs-card id="solution-card">
        <template #title>
          <div class="solution-user-info">oldner</div>
        </template>
        <template #text>
          <div class="solution-content">
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
.solution-card-content {
  width: 100%;
}

.solution {
  width: 100%;
  z-index: 2;
}

.solution .vs-card {
  min-width: 100% !important;
  background-color: #99be9a;
  color: #f3f3f3;
}

.solution-user-info {
  padding: 10px 5px;
  font-size: 12pt;
}

.solution-content {
  padding: 10px 5px;
  font-size: 12pt;
}

.solution-content h3 {
  margin-bottom: 20px;
}
</style>