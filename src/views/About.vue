<template>
  <div style="margin-bottom: 80px">
    <h1>Hello!</h1>

    <div class="paragraph">
      <div>
        Welcome to my webpage! Here you can find some works that i've made
        through my career. I'm <strong>Benjamín Zárate</strong>, a programmer
        and game designer.<br />
        I have a degree on Game Design and have experience building game for PC,
        mobile and VR
      </div>

      <div style="margin-top: 20px">
        I've worked on different kind of
        <router-link to="/game-projects">games</router-link>
      </div>

      <div style="margin-top: 40px">
        I'm always working on new things to push myself.
      </div>
    </div>

    <div style="clear: both"></div>
  </div>
</template>

<style scoped>
.paragraph {
  max-width: 700px;
  margin-bottom: 20px;
}

.photo {
  margin-top: 50px;
  text-align: center;
}

@media only screen and (min-width: 620px) {
  .paragraph {
    float: left;
  }

  .photo {
    float: left;
    padding: 10px;
    padding-left: 80px;
  }
}
</style>