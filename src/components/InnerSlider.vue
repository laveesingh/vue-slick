<template>
  <div class="slick-slider slick-initialized">
    <div class="slick-list">
      <Tracks>
        <slot />
      </Tracks>
    </div>
  </div>
</template>

<script>
import Track from './Track.vue'
export default {
  name: 'inner-slider',
  components: {
    Tracks: Track,
  },
}
</script>
