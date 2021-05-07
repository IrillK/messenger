<template>
  <div class='v-header'>
    <button class="btn">Мессенжер</button>
    <div class="btn-field"> 
      <button class="btn">Редактировать профиль</button>
      <button class="btn">Список поьзователей</button>
      <button class="btn">Выйти</button>
    </div>
  </div>
</template>

<script>

  export default {
    name: "v-header",
    props: {},
    data() {
      return {}
    },
    computed: {
    },
    methods: {}
  }
</script>

<style lang="scss">
  .v-header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: #0b183c ;
    padding: 16px;
    position: fixed;
    width: 100%;
    top: 0;
    left: 0;


    .btn-field {
      padding: 16px;
      position: relative;
      
      display: flex;
      justify-content: center;
    }

    .btn {
      position: relative;
      margin-left: 16px;
      background: transparent;
      border: none;


    }
  }
</style>
