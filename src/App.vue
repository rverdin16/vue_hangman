<template>
  <div id="app" class="container">
    <Heading />
    <Figure />
    <PopUp />
    <Notification />
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import Heading from './components/Heading.vue'
import Figure from './components/Figure.vue'
import PopUp from './components/PopUp.vue'
import Notification from './components/Notification.vue'

export default Vue.extend({
  name: 'App',
  components: {
    Heading,
    Figure,
    PopUp,
    Notification
  }
})
</script>

<style lang="scss">
@import "src/styles/style.scss";

</style>
