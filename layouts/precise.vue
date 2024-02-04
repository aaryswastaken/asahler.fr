<script>
  import "~/assets/css/precise.css"
</script>

<template>
  <div>
    <div id="headerDiv">
      <div id="header">
	<div id="root" @click="navigateTo('/')"> 
	  <slot name="root"> asahler </slot>
	</div> 
	/<slot name="page">
	   500_page
	</slot>
      </div>
    </div>

    <main>
      <slot />
    </main>
  </div>
</template>
