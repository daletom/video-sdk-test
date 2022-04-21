<script setup>
//import {IxVideo} from '@imgix/shared-wc'
import {IxVideo} from '@imgix/web-components'
</script>

<template>
  <main>
    <div
    class="mobile"
    style="display: flex; justify-content: center; margin: auto"
    width="600px"
    height="400px"
  >
    <ix-video
      controls
      source="https://tomgcs.imgix.video/izzy_dance_party.mp4"
    ></ix-video>
  </div>
  </main>
</template>
