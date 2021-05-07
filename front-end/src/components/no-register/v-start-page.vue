<template>
  <div class="v-start-page">
    <v-header-noregister />
    <sign-up-form></sign-up-form>
    <sign-in-form></sign-in-form>
  </div>
</template>

<script>
  import vHeaderNoregister from './layouts/v-header-noregister'
  import signUpForm from './no-register/sign-up-form'
  import signInForm from './no-register/sign-in-form'
  
  export default {
    name: 'v-start-page',
    components: {
      vHeaderNoregister,
      signUpForm,
      signInForm,
    },
    props: {},
    data() {
      return {
        title: 'v-start-page'
      }
    },
    computed: {},
    methods: {},
    watch: {}
  }
</script>

<style>
  .v-start-page {
    margin: 0 auto;
  }
</style>
