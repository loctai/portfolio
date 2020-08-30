<template>
  <div id="skills">
    <h1>Skills</h1>
    <div class="skill-div">
      <img
        alt
        title="HTML5"
        class="skill-icons"
        src="../assets/html5.svg"
        height="75rem"
      />
      <img
        alt
        title="CSS3"
        class="skill-icons"
        src="../assets/css3.svg"
        height="75rem"
      />
      <img
        alt
        title="Bootstrap4"
        class="skill-icons"
        src="../assets/bootstrap-4.svg"
        height="75rem"
      />
      <img
        alt
        title="Vue.js"
        class="skill-icons"
        src="../assets/vue-9.svg"
        height="75rem"
      />
      <img
        alt
        title="React.js"
        class="skill-icons"
        src="../assets/react.svg"
        height="75rem"
      />
      <img
        alt
        title="Python"
        class="skill-icons"
        src="../assets/python-4.svg"
        height="75rem"
      />
      <img
        alt
        title="Git"
        class="skill-icons"
        src="../assets/git-icon.svg"
        height="75rem"
      />
      <img
        alt
        title="Github"
        class="skill-icons"
        src="../assets/github-1.svg"
        height="75rem"
      />
      <img
        alt
        title="Express"
        class="skill-icons"
        src="../assets/express-109.svg"
        height="75rem"
      />
      <img
        alt
        title="Node.js"
        class="skill-icons"
        src="../assets/nodejs-icon.svg"
        height="75rem"
      />
      <img
        alt
        title="MongoDB"
        class="skill-icons"
        src="../assets/mongo.svg"
        height="75rem"
      />
    </div>
  </div>
</template>

<script>
export default {
  name: "Skills"
};
</script>

<style lang="scss" scoped>
#skills {
  min-height: 80vh;
  display: flex;
  justify-content: center;
  padding: 1rem 10rem;
  align-items: center;
  flex-direction: column;
  .skill-div {
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
  }
  .skill-icons {
    border-radius: 6px;
    opacity: 0.8;
    padding: 1rem 2rem;
    transition: all 0.2s ease-in-out;
    &:hover {
      transform: translateY(-10px);
      opacity: 1;
    }
  }
}
@media only screen and (max-width: 500px) {
  #skills {
    padding: 1rem 1rem;
  }
  .skill-icons {
    padding: 1rem 1rem;
  }
}
</style>
