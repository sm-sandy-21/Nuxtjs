<template>
      <div>
            <h1>Single User Vue</h1>
            <h1>User Id : {{ $route.params.id }}</h1>
            </div>
</template>

<script>
export default {
      validate(data){
      //     console.log(data.route)
      //     return true

      // return data.params.id == 1

      // return Only Validate Number

      return /^\d+$/.test(data.params.id)
      }
}
</script>