<script setup>
  import "~/assets/css/Social.css"

  const props = defineProps(["redirect"])
</script>

<template>
  <button id="mainBtn" @click="navigateTo(props.redirect, {external: true})">
    <slot />
  </button>
</template>
