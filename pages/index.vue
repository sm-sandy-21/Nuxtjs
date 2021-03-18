<template>
  <div class="container">
    <h1>Home Page(Routing,Pages,Layout,Change Page title Using head) </h1>
    <h2><a href="/users">Go to User Page (a)</a></h2>
    <p>When we use anger tag (a) this is send the request on server and then redering the page "It Takes Some Time"</p>
  
  <h2><nuxt-link to="/users">Go to Users (nuxt Link)</nuxt-link></h2>
   <p>faster then anger tage (Without Send Request)</p><br>

   <nuxt-link to="/Users">New User</nuxt-link>
  </div>
</template>

<script>
export default {}
</script>

<style>

</style>
