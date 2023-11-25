
import type { divider } from '@nuxt/ui/dist/runtime/ui.config';
<template>
  <div>
    <UCard background="flex gap-2">
      <img class="hero" src="https://plus.unsplash.com/premium_photo-1700124504129-02393b281f06?q=80&w=2160&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D">
      <div>Title</div>
      <div>Content</div>
    </UCard>
  </div>
</template>

<script lang="ts" setup>

</script>

<style>
.hero{
  @apply w-56
  h-auto 
  object-cover

}
</style>