<script setup>
  import '~/assets/css/Button.css'

  const emit = defineEmits(["clicked"])
</script>

<template>
  <button class="bigButton" @click="$emit('clicked')">
    <slot/>
  </button>
</template>
