<template>
  <div class='v-header-noregister'>
    <p>Messenger</p>
  </div>
</template>

<script>
 

  export default {
    name: "v-header-noregister",
    props: {},
    data() {
      return {}
    },
    computed: {},
    methods: {}
  }
</script>

<style lang="scss">
  .v-header-noregister {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: #0b183c;
    padding: 16px;
    position: fixed;
    width: 100%;
    top: 0;
    left: 0;

    img {
      width: 50px;
    }
    p{
      font-size: 20px;
      color: white;
    }


    .search_btn {
      margin-left: 16px;
      background: transparent;
      border: none;
    }
  }
</style>
