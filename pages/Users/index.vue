<template>
      <div>
        <h1>User page</h1>
        <input type="text" placeholder="Enter Id" v-model="userId">
        <button @click="submit">Go _Id Page</button>
      </div>
</template>

<script>
      export default {
          data() {
                return {
                      userId:""
                }
          }, 
          methods:{
                submit(){
                   this.$router.push('/users/' + this.userId)
                }
          } 
      }
</script>

<style lang="scss" scoped>

</style>