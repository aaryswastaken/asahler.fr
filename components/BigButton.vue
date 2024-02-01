<<script>
  import '~/assets/css/Button.css'
</script>

<template>
  <button class="bigButton" @click="$emit('click')">
    <slot/>
  </button>
</template>
