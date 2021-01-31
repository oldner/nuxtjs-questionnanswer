<template>
  <div class="issue-main">
    <div class="navbar-issues"></div>
    <div class="content">
      <div class="leftside"></div>
      <div class="middleside">
        <div class="center content-inputs search-field">
          <vs-input id="search-input" placeholder="Sorun ara.." />
        </div>
        <div class="center add-issue">
          <vs-button danger border>SORUNUM VAR!</vs-button>
        </div>
        <div class="sort-issues">
          <ul>
            <li><a href="#">bugün</a></li>
            <li><a href="#">bu ay</a></li>
            <li><a href="#">bu yıl</a></li>
            <li><a href="#">tüm zamanlar</a></li>
          </ul>
        </div>
        <div class="issues">
          <issue-card-icon></issue-card-icon>
          <vs-card>
            <template #title>
              <h3>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Ab
                maxime commodi sed non rem officia nulla, nam nesciunt saepe
                magni?
              </h3>
            </template>
            <template #text>
              <div class="textt">hako tarafindan 3 saat once gonderildi</div>
            </template>
          </vs-card>
          <issue-card-icon></issue-card-icon>
          <vs-card>
            <template #title>
              <h3>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Ab
                maxime commodi sed non rem officia nulla, nam nesciunt saepe
                magni?
              </h3>
            </template>
            <template #text>
              <div class="textt">hako tarafindan 3 saat once gonderildi</div>
            </template>
          </vs-card>
          <issue-card-icon></issue-card-icon>
          <vs-card>
            <template #title>
              <h3>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Ab
                maxime commodi sed non rem officia nulla, nam nesciunt saepe
                magni?
              </h3>
            </template>
            <template #text>
              <div class="textt">hako tarafindan 3 saat once gonderildi</div>
            </template>
          </vs-card>
        </div>
      </div>
      <div class="rightside"></div>
    </div>
  </div>
</template>

<script>
import IssueCardIcon from "~/components/Issues/Home/IssueCardIcon.vue";

export default {
  components: {
    IssueCardIcon,
  },
};
</script>

<style>
.issue-main {
  background-color: #e5eae3;
}

.navbar-issues {
  width: 100%;
  height: 50px;
  background-color: rgb(250, 206, 206);
}

.content {
  display: flex;
  justify-content: space-between;
  width: 100%;
}

.leftside {
  width: 15%;
}

.middleside {
  width: 60%;
}

.rightside {
  width: 15%;
}

.search-field {
  display: flex;
  justify-content: center;
}

#search-input input {
  width: 600px !important;
  margin: 30px 0;
}

.add-issue {
  width: 100%;
}

.add-issue button {
  background-color: rgb(255, 71, 87);
  color: #f3f3f3;
  width: 400px;
  height: 40px;
  margin: 10px auto;
  font-size: 18pt;
}

.sort-issues {
  width: 100%;
  margin-left: auto;
  display: flex;
  justify-content: flex-end;
}

.sort-issues ul {
  padding: 0;
  margin: 0;
  list-style: none;
}

.sort-issues ul li {
  display: inline-block;
  padding: 0 5px;
  border-left: 1px solid #b0b0b0;
}

.sort-issues ul li:first-child {
  border-left: none;
}

.sort-issues ul li a {
  color: #b0b0b0;
  text-decoration: none;
}

.issues .vs-card {
  min-width: 100% !important;
  padding: 10px 5px !important;
  margin: 10px 0;
}

.textt {
  float: right;
}
</style>