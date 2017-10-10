<template>
  <main-layout>
    <p>Welcome home</p>
    <md-button>默认</md-button>
	<md-button class="md-primary">主要</md-button>
	<md-button class="md-accent">吸引</md-button>
	<md-button class="md-warn">暖色</md-button>
	<md-button class="md-primary" disabled>禁用</md-button>
	<md-button class="md-dense">浓厚</md-button>
  </main-layout>
</template>

<script>
  import MainLayout from '../layouts/Main.vue'

  export default {
    components: {
      MainLayout
    }
  }
</script>
