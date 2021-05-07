<template>
  <div class='v-account-item'>
    <img class="v-account-item__photo" :src=" require('../../assets/images/' + account_data.image) " alt="img">
    <div>
      <p class="v-account-item__surname">{{account_data.surname}}</p>
      <p class="v-account-item__name">Price: {{account_data.name }}</p>
    </div>
    <button></button>
    
</template>

<script>
  export default {
    name: "v-catalog-item",
    components: {},
    props: {
      account_data: {
        type: Object,
        default() {
          return {}
        }
      }
    },
    data() {},
    computed: {},
    methods: {},
    mounted() {
      this.$set(this.account_data, 'quantity', 1)
    }
  }
</script>

<style lang="scss">
  .v-catalog-item {
    flex-basis: 25%;
    box-shadow: 0 0 8px 0 #e0e0e0;
    padding: $padding*2;
    margin-bottom: $margin*2;

    &__image {
      width: 100px;
    }
  }
</style>
