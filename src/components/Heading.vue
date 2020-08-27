<template>
    <div class="heading">
        <h1 class="main-heading">Let's play Hangman</h1>
        <h2 class="sub-heading">Find the hidden word by entering a letter</h2>
    </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  components: {

  }
})
</script>

<style lang="scss">
@import "src/styles/style.scss";

.heading{
    text-align: center;
    margin-top: 2rem;
}
</style>
