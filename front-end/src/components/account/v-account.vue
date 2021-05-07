<template>
  <div class='v-account'>
    <div class="v-catalog__list">
      <v-catalog-item
          v-for="account in account_data"
          :key="account.id"
          :account_data="account"
      />
    </div>
  </div>
</template>

<script>
  import vAccountItem from './v-account-item'

  export default {
    name: "v-account",
    components: {
      vAccountItem,
    },
    props: {},
    data() {
      return {},
    },
    methods: {},
    mounted() {}
  }
</script>

<style lang="scss">
  .v-account {
    &__list {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-between;
      align-items: center;
    }

</style>
