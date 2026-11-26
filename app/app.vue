<script setup lang="ts">
const clicks = ref(0)

function increment() {
  clicks.value++
}
</script>

<template>
  <div>
    <NuxtRouteAnnouncer />
    <NuxtWelcome />
    <h1>Test github</h1>
    <button type="button" @click="increment">
      Cliqué {{ clicks }} fois
    </button>
  </div>
</template>
