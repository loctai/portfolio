<template>
  <div id="about">
    <h1>
     Hi, I'm a Full Stack Web / App Developer.
      <span id="hi">👋</span>
    </h1>
    <p>
       For more than 2 years, I’ve worked on various projects involving both front-end and back-end development.
    </p>

    <p>
      got any questions?
      <a href="#contact">Contact me.</a>
    </p>
  </div>
</template>

<script>
export default {
  name: "About"
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
$blue: #2257ea;
#about {
  display: flex;
  flex-direction: column;
  justify-content: space-around;
  align-items: center;
  font-size: 1.4rem;
  padding: 1rem 10rem;
  min-height: 100vh;
  p {
    text-align: center;
    a {
      text-decoration: none;
      color: $blue;
    }
  }
  h1 {
    text-align: center;
  }
}
#hi {
  animation: shake 0.5s infinite ease-in-out alternate;
  display: inline-block;
  z-index: 0;
}
@media only screen and (max-width: 500px) {
  #about {
    padding: 1rem;
  }
}
@keyframes shake {
  from {
    transform: rotate(0deg);
  }
  to {
    transform: rotate(20deg);
  }
}
</style>
