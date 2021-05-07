<template>
   <div class="v-catalog">
      <v-catalog-item></v-catalog-item>
      <v-catalog-item></v-catalog-item>

   </div>
</template>

<script>
   import vCatalogItem from '../components/v-catalog-item.vue'
   //import vCart from '../components/v-cart.vue'

   export default{
      name: 'v-catalog',
      components:{
         vCatalogItem,
         //vCart,
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
   .v-catalog{
      &__list{
         display: flex;
         justify-content: space-between;
         align-items: center;
         flex-wrap: wrap; 
      }
   }
</style>