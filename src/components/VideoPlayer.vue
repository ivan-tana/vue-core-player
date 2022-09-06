<script>
import Vue from 'vue'
import VueCoreVideoPlayer from 'vue-core-video-player'
Vue.use(VueCoreVideoPlayer)

</script>

<template>
  <div class="player-container">
    <vue-core-video-player @play="your_method" src="http://playertest.longtailvideo.com/adaptive/bipbop/gear4/prog_index.m3u8"></vue-core-video-player>
  </div>
</template>

