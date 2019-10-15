<template>
  <div class="home">
    <h1>Camera</h1>
    <vue-web-cam v-bind:selectFirstDevice="true"/>
  </div>
</template>

<script>
// @ is an alias to /src
import { WebCam } from "vue-web-cam"

export default {
  name: 'camera',
  components: {
    "vue-web-cam": WebCam
  }
}
</script>
