<template>
      <div>
            <h1>New User Page</h1>
             <input type="text" placeholder="Enter Id" v-model="userId">
             <button @click="submit">Go _Id Page</button>

<br><br><br>
            <p>In The Page directoy, you can see 2 User Component, one folder ,another without folder 
                 <br> ...This is Root User....when you call same user child component you will use nuxt-child
            </p>

             <nuxt-child />

             
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
          },
          layout: 'userLayout',
         head(){
               return {
                     title:"Users"
               }
         }

      }
</script>

<style lang="scss" scoped>

</style>