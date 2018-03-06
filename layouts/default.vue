<template>
  <div class="container mx-auto app">
      <app-header></app-header>
    <nuxt/>
  </div>
</template>

<script type="text/javascript">
import Header from '@/components/Header'

export default {
    components: {
        AppHeader: Header
    }
}
</script>

<style>
.app {
    
}
</style>
