<template>
  <div>
    <a href="intent://arvr.google.com/scene-viewer/1.0?mode=ar_preferred&disable_occlusion=true&enable_vertical_placement=true&file=https%3A%2F%2Fs3.eu-west-2.amazonaws.com%2Fproduct.baetes.com%2FP7650933_Tiger_30x40_WEBB.glb#Intent;scheme=https;package=com.google.ar.core;action=android.intent.action.VIEW;S.browser_fallback_url=https%3A%2F%2Far.baetes.com%2FP7650933_Tiger_30x40_WEBB%3F%26text%3DTESTA%2BI%2BHEMMAMILJ%25c3%2596%23model-viewer-no-ar-fallback;end">
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
