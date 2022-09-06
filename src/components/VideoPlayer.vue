<script>
import Vue from 'vue'
import VueCoreVideoPlayer from 'vue-core-video-player'
Vue.use(VueCoreVideoPlayer)

</script>

<template>
  <div class="player-container">
    <vue-core-video-player @play="your_method" src="http://commondatastorage.googleapis.com/gtv-videos-bucket/sample/TearsOfSteel.mp4"></vue-core-video-player>
  </div>
</template>

