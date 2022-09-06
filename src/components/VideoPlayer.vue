<script>
import Vue from 'vue'

import VueCoreVideoPlayer from 'vue-core-video-player'
import HLSCore from '@core-player/playcore-hls'


Vue.use(VueCoreVideoPlayer)

export default {
  data () {
    return {
      HLSCore,
      url:"http://playertest.longtailvideo.com/adaptive/bipbop/gear4/prog_index.m3u8"
    }
  }
}

</script>

<template>
  <div class="player-container">
    <vue-core-video-player :core="HLSCore" :src="url"></vue-core-video-player>
  </div>
</template>

