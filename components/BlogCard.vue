
<template>
  <div>
    <UCard :ui="{
      background : 'flex'
    }">
      <img class="hero"
        :src="post.img">
      <div class="">
        <div class="text-4xl font-bold">{{post.title}}</div>
        <div class="text-sm">{{ post.content }}</div>
      </div>
    </UCard>
  </div>
</template>

<script lang="ts" setup>
const props = defineProps(['post'])
</script>

<style>
.hero {
  @apply w-56 h-auto object-cover rounded-md
}
</style>