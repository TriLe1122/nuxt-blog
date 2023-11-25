<template>
  <div class="flex flex-wrap gap-2">
    <div v-for="post in posts">
      <BlogCard :post="post"/>
    </div>
  </div>
</template>


<script lang="ts" setup>
import { appState } from '~/appState';
const posts = appState.posts


</script>


<style lang="css" scoped>

</style>~/appState