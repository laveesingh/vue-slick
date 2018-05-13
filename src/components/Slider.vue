<template>
  <InnerSlider>
    <slot />
  </InnerSlider>
</template>
<script>
import InnerSlider from './InnerSlider.vue'
export default {
  name: 'slider',
  components: {
    InnerSlider,
  },
  beforeCreate: function() {
    console.log(this.$slots)
  },
}
</script>

<style>
@import 'https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.6.0/slick.min.css';
@import 'https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.6.0/slick-theme.min.css';
</style>
