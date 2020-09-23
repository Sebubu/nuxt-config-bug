<template>
  <div class="container">
    <h1>Nuxt Config bug</h1>

    <p style="margin-top: 6px;">publicRuntimeConfig is not available when deployed to vercel.com.</p>

    <p style="margin-top: 20px; font-weight: bold;">this.$config:</p>

    <div style="margin-left: 4px;">
          {{config}}

    </div>
    
  </div>
</template>

<script>


export default {
  components: {

  },
  data() {
    return {
      config: this.$config
    }
  }
}
</script>

<style>

</style>
