<template>
  <div style="margin-bottom: 80px">
    <h1>Hello!</h1>

    <div class="paragraph">
      <div>
        Welcome to my webpage! Here you can find some works that i've made
        through my career. I'm <strong>Benjamín Zárate</strong>, a gameplay
        programmer and game designer.<br />
        I'm open to learn new technologies and try new challenges
      </div>

      <div style="margin-top: 20px">
        Here you can find different
        <router-link to="/game-projects">projects</router-link> that I've worked
        on
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