<template>
  <div class="container">
    <ul>
      <li>
        <v-link href="/"><md-button href="/">Add</md-button></v-link>
        <v-link href="/about"><md-button href="/">Addd</md-button></v-link>
      </li>
    </ul>
    <md-toolbar md-theme="orange">
  <md-button class="md-icon-button">
    <md-icon>menu</md-icon>
  </md-button>

  <h2 class="md-title" style="flex: 1">Vue Material</h2>

  <md-button href="/">Add</md-button>
  <md-button href="/about">Remove</md-button>
</md-toolbar>
    <slot></slot>
  </div>
</template>

<script>
  import VLink from '../components/VLink.vue'

  export default {
    components: {
      VLink
    }
  }
</script>

<style scoped>
  .container {
    max-width: 600px;
    margin: 0 auto;
    padding: 15px 30px;
    background: #f9f7f5;
  }
</style>
