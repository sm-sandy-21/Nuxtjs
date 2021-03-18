<template>

  <div>
        <app-header></app-header>
        <header><h1>User Layout Sectoin</h1></header>
        <br>
    <Nuxt />
  </div>
</template>

<script>
import appHeader from '~/components/appHeader'
export default {
      components : {
            appHeader
      }
}
</script>