<template>
  <div id="projects">
    <h1>My Projects</h1>
    <div class="card-deck">
      <CardComp
        main="Binary Options Trading"
        desc=""
        img_source="https://i.imgur.com/imGkt7t.jpg"
        weblink="#"
        gitlink="#"
      ></CardComp>
      <CardComp
        main="Cryptocurrency Wallet"
        desc=""
        img_source="https://i.imgur.com/JnsS4tT.png"
        weblink="#"
        gitlink="#"
      ></CardComp>
      <CardComp
        main="Cryptocurrency Wallet"
        desc=""
        img_source="https://i.imgur.com/fwSX0Ev.png"
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
  min-height: 60vh;
  .card-deck {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
  }
}
</style>
