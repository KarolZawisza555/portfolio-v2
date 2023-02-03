<template>
  <v-col cols="12" class="d-flex justify-center ma-4 animate__animated animate__backInDown">
    <v-row class="about-me d-none d-md-flex">
      <v-col cols="7">
        <p class="text-h3 mt-12 text-white font-weight-bold">Zawisza Karol</p>
        <p class="text-h4 mb-5 mt-3 text-white font-weight-bold">Frontend developer</p>
      </v-col>
      <v-col cols="5">
        <v-avatar size="250">
          <v-img src="../assets/kz.png" />
        </v-avatar>
      </v-col>
    </v-row>
    <v-row class="about-me d-flex d-md-none">
      <v-col cols="12">
        <v-avatar size="350" class="bg1">
          <v-img src="../assets/kz.png" />
        </v-avatar>
      </v-col>
      <v-col cols="12">
        <p class="text-h3 mt-7 text-white font-weight-bold">Zawisza Karol</p>
        <p class="text-h4 mt-3 text-white font-weight-bold">Frontend developer</p>
      </v-col>
    </v-row>
  </v-col>
  <v-col cols="12" class="d-flex justify-center">
    <v-card variant="tonal" max-width="1000">
      <p class="text-h3 py-3 text-white font-weight-bold">
        About me
      </p>
      <p class="text-h6 text-white ">
        Engineer with a passion for IT and increasing productivity. I have a passion for creating engaging and
        interactive user experiences. With 2 years of experience in the field, I have a solid understanding of HTML,
        CSS,
        and JavaScript and have experience working with a variety of front-end frameworks such as Vue and React.I am
        constantly seeking new challenges and opportunities to expand my skillset and stay up-to-date with the latest
        industry trends and technologies.I am a team player and enjoy collaborating with designers, back-end developers,
        and clients to deliver solid results.
      </p>
    </v-card>
  </v-col>
</template>

<script>
//
export default {
  data() {
    return {
    }
  },
};
</script>

<style>
.about-me {
  max-width: 1100px;
  width: 100%;
}

.bg1 {
  background: radial-gradient(100% 0% at left, white 30%, transparent 51.1%);
}

.bg1a {
  background: radial-gradient(100% 250% at left, transparent 50%, white 50.1%);
}

.bg2 {
  background: radial-gradient(100% 200% at left, #72A9E8 50%, #1867c0 50.1%);
}

.bg3 {
  background: linear-gradient(140deg, transparent 60%, white 60%);
}
</style>

