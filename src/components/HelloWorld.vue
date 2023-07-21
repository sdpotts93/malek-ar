<template>
  <div>
    <a href="intent://arvr.google.com/scene-viewer/1.0?mode=ar_preferred&disable_occlusion=true&enable_vertical_placement=true&file=https%3A%2F%2Fmy-personal-assets.s3.us-west-1.amazonaws.com%2Fmatisse.gltf#Intent;scheme=https;package=com.google.ar.core;action=android.intent.action.VIEW;S.browser_fallback_url=https%3A%2F%2Fwww.studiomalek.com%2F%23model-viewer-no-ar-fallback;end">
      <button>
        BUTTON
      </button>
    </a>
  </div>
</template>

<script>
import '@ar-js-org/ar.js/aframe/build/aframe-ar';

export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  methods: {

  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
