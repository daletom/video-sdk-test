<script setup>
//import {IxVideo} from '@imgix/shared-wc'
import {IxVideo} from '@imgix/web-components'
</script>

<template>
  <main>
    <div
    style="width: 500px; height: 500px; display: flex; justify-content: center; margin: auto"
  >
    <ix-video
      width="600"
      height="400"
      controls
      source="https://tomgcs.imgix.video/izzy_dance_party.mp4"
    ></ix-video>
  </div>
  </main>
</template>
