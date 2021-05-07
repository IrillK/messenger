<template>
  <div class='sign-up-form'>
    <form>
      <h1 class="h3 mb-3 fw-normal">Please sign up</h1>

      <div class="form-floating">
        <input type="email" class="form-control" id="floatingInput" placeholder="name@example.com">
        <label for="floatingInput">Login</label>
      </div>
      <div class="form-floating">
        <input type="password" class="form-control" id="floatingPassword" placeholder="Password">
        <label for="floatingPassword">Password</label>
      </div>

      <div class="checkbox mb-3">
        <label>
          <input type="checkbox" value="remember-me"> Remember me
        </label>
      </div>
      <button class="w-100 btn btn-lg btn-primary" type="submit">Sign up</button>
  </form>
  </div>
</template>

<script>
  export default {
    name: "sign-up-form",
    props: {},
    data() {
      return {}
    },
    computed: {}
  }
</script>

<style lang="scss">
  .sign-up-form{
    width: 20%;
    padding: 8px;
    margin: 8px;
    text-align: justify;
    display: inline-block;
  }
</style>

