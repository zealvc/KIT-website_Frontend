<template>
  <span>
    <v-container
      fluid
      fill-height
      class="home-hero hidden-sm-and-down"
      style="max-height: 100vh;"
    >
      <v-layout
        justify-start
        row
      >
        <v-flex
          md5
          class="offset-md1"
        >
          <h1 style="padding-top: 70px; padding-bottom: 20px;">
            Welcome to KIT
          </h1>
          <em style="font-size: 25px;">
            Watch the Season Final Now
          </em>
          <p style="padding-top: 20px;">
            This is the KIT website.KIT is the best school in cambodia.<br>Kirirom Institute of Technology is the best Technology school in CAMBODIA.
          </p>
        </v-flex>
      </v-layout>
      <!--<v-spacer/>-->
      <!--<v-btn style="background-color: red">APPLY NOW</v-btn>-->
    </v-container>
    <!--For phone-->
    <v-container class="hidden-md-and-up" />
  </span>
</template>

<script>
export default {
  name: 'HomeHero',
  components: {}
}
</script>

<style scoped>
.home-hero {
  background: url('https://kit.edu.kh/assets/images/slider/slider1.jpg');
  background: url('https://kit.edu.kh/assets/images/slider/slider3.jpg');
  background: url('https://kit.edu.kh/assets/images/slider/slider2.jpg');
  background-size: cover;
  width: 100%;
  height: 100%;
  margin-top: -70px;
  padding-top: 70px;
}
</style>
