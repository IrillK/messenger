<template>
   <div class="v-catalog-item">
      <p>Item 1</p>
      <p>Price: 100</p>
      <button>Add to cart</button>

   </div>
</template>

<script>
   

   export default{
      name: 'v-catalog-item',
      components:{
      },
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
   .v-catalog-item {
      flex-basis: 25%;
      box-shadow: 0 0 8px 0 #e0e0e0;
      padding: 16;
      margin-bottom: 16;
      width: 300px
   }
</style>