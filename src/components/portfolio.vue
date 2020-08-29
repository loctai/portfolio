<template>
  <div id="projects">
    <h1>My Projects</h1>
    <div class="card-deck">
      <CardComp
        main="memory-game"
        desc=""
        img_source="https://i.imgur.com/Ze5rpfr.jpg"
        weblink="#"
        gitlink="#"
      ></CardComp>
      <CardComp
        main="Todone"
        desc=""
        img_source="https://i.imgur.com/Ze5rpfr.jpg"
        weblink="#"
        gitlink="#"
      ></CardComp>
      <CardComp
        main="weather-app"
        desc=""
        img_source="https://i.imgur.com/Ze5rpfr.jpg"
        weblink="#"
        gitlink="#"
      ></CardComp>
    </div>
  </div>
</template>

<script>
import CardComp from "./card";
export default {
  name: "Portfolio",
  components: {
    CardComp
  }
};
</script>

<style lang="scss" scoped>
#projects {
  display: flex;
  justify-content: space-around;
  align-items: center;
  flex-direction: column;
  min-height: 100vh;
  .card-deck {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
  }
}
</style>
