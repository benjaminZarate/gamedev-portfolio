<template>
  <div>
    <h1>Resume</h1>

    <div class="paragraph">
      I'm <strong>Benjamín Zárate</strong>, a gameplay programmer. I have a
      degree on game design but i specialize on programming. <br />
      I work with Unity since 2017 and i've worked on a variaty of projects: PC,
      mobile and VR
      <br />

      <div style="margin-top: 20px; margin-bottom: 20px">
        <a class="download-link" href="d/CV-espanol.pdf" target="_blank"
          ><i class="fa fa-download fa-lg fa-fw"></i>Descargar como PDF</a
        >
        <div style="clear: both"></div>
      </div>
      <div style="margin-top: 20px; margin-bottom: 20px">
        <a class="download-link" href="d/CV-english.pdf" target="_blank"
          ><i class="fa fa-download fa-lg fa-fw"></i> Download as PDF</a
        >
        <div style="clear: both"></div>
      </div>
    </div>

    <div style="clear: both"></div>

    <div class="full-content">
      <h2><strong>Work experience</strong></h2>

      <h3>Internship - InvadeLab, Santiago (Chile)</h3>
      <h4>January 2019 - March 2019</h4>

      <div>VR prototypes working with Unity 2018 and Oculus GO</div>

      <div class="tech-stack">
        I made a 360 image gallery, an interactive 360 video player and some
        games.
      </div>

      <h3>Dirty Wars - September 11</h3>
      <h4>June 2019 - March 2020</h4>

      <div>Incharge of player mechanics and IA</div>

      <div class="tech-stack">
        I was incharge of make the player movement mechanics, IA behaviour
        (Idle, alert, Attack), puzzle solving, etc. in a stealth game.
      </div>

      <h2>Skills</h2>

      <div class="skill-set">
        <h3><strong>Programming Languages</strong></h3>
        <div>C#</div>
        <div>Dart</div>
      </div>

      <div class="skill-set">
        <h3><strong>Software</strong></h3>
        <div>Unity</div>
        <div>Blender</div>
        <div>Adobe Premiere Pro</div>
        <div>Adobe After Effects</div>
        <div>Adobe Photoshop</div>
      </div>
      <div style="clear: both" />

      <h2><strong>Education</strong></h2>

      <h3>Instituto Profesional ARCOS 2016 - 2020</h3>
      <h4>Game Designer degree</h4>

      <h2><strong>Languages</strong></h2>

      <h3>Spanish</h3>
      <div>Native</div>

      <h3>English</h3>
      <div>Fluent writing and speaking</div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from "vue";
//import SkillRate from "@/components/SkillRate.vue";

export default Vue.extend({
  name: "Resume",
  // components: {
  //   SkillRate,
  // },
});
</script>

<style scoped>
h2 {
  font-weight: 100;
  font-size: 2em;
  margin: 0px;
  padding: 0px;
  padding-top: 50px;
}
h3 {
  font-weight: 100;
  font-size: 1.6em;
  margin: 0px;
  padding: 0px;
  padding-top: 30px;
}
h4 {
  font-weight: 100;
  font-size: 1.3em;
  margin: 0px;
  padding: 0px;
  padding-top: 15px;
  font-style: italic;
}

.paragraph {
  max-width: 700px;
}

.download-link {
  float: left;
  margin-right: 50px;
}

.full-content div {
  max-width: 800px;
}

.skill-set h3 {
  padding-bottom: 10px;
}

.photo img {
  height: 300px;
  width: 300px;
}

.tech-stack {
  font-style: italic;
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
    padding: 30px;
    padding-left: 80px;
  }

  .skill-set {
    float: left;
    padding-right: 60px;
  }
}
</style>