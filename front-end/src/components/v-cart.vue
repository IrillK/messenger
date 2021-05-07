<template>
   <div class="v-cart">
      <p>vvvv</p>
   </div>
</template>

<script>
   

   export default{
      name: 'v-cart',
      components:{},
      props: {},
      data(){
         return{
            title: 'v-catalog',
            title2: 'v-catalog',
         }
      },
      computed:{},
      methods:{},
      watch:{},
      mounted(){
         console.log('Hello? i am alive!')
      }
   }
</script>
<style>
   .v-main-wrapper{
      display: flex;
      justify-content: center;
      align-items: center;
      max-width: 900px;
      margin: 0 auto;
   }
</style>