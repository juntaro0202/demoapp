<template>
  <div>
    <youtube width="300" height="200" :video-id="videoId" />
  </div>
</template>

<script>
import Vue from "vue";
import VueYoutube from "vue-youtube";

Vue.use(VueYoutube);

export default {
  data() {
    return {
      videoId: "fHuO3Xaje98"
    };
  }
};
</script>
