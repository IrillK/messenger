<template>
  <div class="v-main-wrapper">
      <v-header></v-header>
      <v-account></v-account>
  </div>
</template>

<script>
  import vHeader from './layouts/v-header'
  //import vMakeProfile from './no-register/v-make-profile'
  import vAccount from './account/v-account'

  export default {
    name: 'v-main-wrapper',
    components: {
      vHeader,
      //vMakeProfile,
      //signUpForm,
      //signInForm,
      

    },
    props: {},
    data() {
      return {
        title: 'Main wrapper'
      }
    },
    computed: {},
    methods: {},
    watch: {}
  }
</script>

<style>
  .v-main-wrapper {
    margin: 0 auto;
  }
</style>
