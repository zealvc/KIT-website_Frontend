<template>
  <span>
    <v-container
      fluid
      fill-height
      class="home-hero hidden-sm-and-down pa-0"
      style="max-height: 100vh;"
    >
      <v-carousel hide-controls height="700px">
      <v-carousel-item
        v-for="(item,i) in items"
        :key="i"
        :src="item.src"
      ></v-carousel-item>
    </v-carousel>
      <v-layout
        justify-start
        row
      >

        <v-flex
          md5
          class="offset-md1"
        >
        </v-flex>
      </v-layout>
    </v-container>
    <v-container class="hidden-md-and-up" />
  </span>
</template>

<script>
export default {
  name: 'HomeHero',
  components: {},
  data() {
    return {
      items: [
        {
          src: 'https://kit.edu.kh/assets/images/slider/slider1.jpg'
        },
        {
          src: 'https://kit.edu.kh/assets/images/slider/slider3.jpg'
        },
        {
          src: 'https://cdn.vuetifyjs.com/images/carousel/bird.jpg'
        },
        {
          src: 'https://cdn.vuetifyjs.com/images/carousel/planet.jpg'
        }
      ]
    }
  }
}
</script>

<style scoped>
.home-hero {
  /*background: url('https://kit.edu.kh/assets/images/slider/slider1.jpg');*/
  /*background: url('https://kit.edu.kh/assets/images/slider/slider3.jpg');*/
  /*background: url('https://kit.edu.kh/assets/images/slider/slider2.jpg');*/
  background-size: cover;
  width: 100%;
  height: 100%;
  margin-top: -170px;
  padding-top: 75px;
}
</style>
