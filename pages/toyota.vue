<template>
  <v-layout>
    <v-flex class="text-center">
      <youtube width="800" height="400" :video-id="videoId" />
    </v-flex>
    <!-- 追加 -->
    <p>
      <v-btn class="ma-2" text icon color="blue lighten-2">
        <v-icon>mdi-thumb-up</v-icon>
      </v-btn>

      <v-btn class="ma-2" text icon color="red lighten-2">
        <v-icon>mdi-thumb-down</v-icon>
      </v-btn>
    </p>
  </v-layout>
</template>

<script>
import Vue from "vue";
import VueYoutube from "vue-youtube";

Vue.use(VueYoutube);

export default {
  data() {
    return {
      videoId: "fExYWri0-fs"
    };
  }
};
</script>
