<template>
  <div class="slick-track">
    <slot />
  </div>
</template>
<script>
export default {
  name: 'tracks',
  beforeCreate: function() {
    console.log(this.$slots)
    this.$slots.default.forEach(slot => {
      if (!slot.data) slot.data = {}
      slot.data.staticClass = 'slick-slide'
    })
  },
}
</script>
