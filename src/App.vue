<template>
  <div id="app">
    <h2>Slider Component</h2>
    <Slider>
      <img src="https://images.pexels.com/photos/257360/pexels-photo-257360.jpeg" alt="nature">
      <img src="http://images.all-free-download.com/images/graphiclarge/canoe_water_nature_221611.jpg" alt="nature">
      <img src="https://images.pexels.com/photos/236047/pexels-photo-236047.jpeg" alt="nature">
      <img src="https://images.pexels.com/photos/257360/pexels-photo-257360.jpeg" alt="nature">
      <img src="http://images.all-free-download.com/images/graphiclarge/canoe_water_nature_221611.jpg" alt="nature">
      <img src="https://images.pexels.com/photos/236047/pexels-photo-236047.jpeg" alt="nature">
    </Slider>
  </div>
</template>

<script>
import Slider from './components/Slider.vue'

export default {
  name: 'app',
  components: {
    Slider,
  },
}
</script>

<style>
</style>
