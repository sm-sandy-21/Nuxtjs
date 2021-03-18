<template>
  <div>
    <app-header></app-header>
    <Nuxt />
  </div>
</template>
<script>
import appHeader from '~/components/appHeader'
export default {
  components:{
    appHeader
  }
}
</script>
<style>
