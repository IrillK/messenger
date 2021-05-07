<template>
  <div class="v-make-profile">
    <div class="col-md-12 col-lg-11">
      <h4 class="mb-3">
      <ya-tr-span data-index="13-0" data-translated="true" data-source-lang="ar" data-target-lang="ru" data-value="عنوان الفوترة" data-translation="Платежный адрес" data-type="trSpan">Создать профиль</ya-tr-span>
      </h4>
      <form novalidate="novalidate" class="needs-validation">
        <div class="row g-3">
          <div class="col-sm-6">
            <label for="firstName" class="form-label">
              <ya-tr-span data-index="14-0" data-translated="true" data-source-lang="ar" data-target-lang="ru" data-value="الاسم الأول" data-translation="Имя" data-type="trSpan">Имя</ya-tr-span>
            </label>
            <input type="text" id="firstName" placeholder="" value="" required="required" class="form-control" style="text-align: left;">
            <div class="invalid-feedback">
              <ya-tr-span data-index="15-0" data-translated="true" data-source-lang="ar" data-target-lang="ru" data-value=" يرجى إدخال اسم أول صحيح. " data-translation=" Пожалуйста, введите имя первого истинного. " data-type="trSpan"> Пожалуйста, введите имя первого истинного. </ya-tr-span>
            </div>
          </div>
          <div class="col-sm-6">
            <label for="lastName" class="form-label">
            <ya-tr-span data-index="16-0" data-translated="true" data-source-lang="ar" data-target-lang="ru" data-value="اسم العائلة" data-translation="Фамилия" data-type="trSpan">Фамилия</ya-tr-span></label>
            <input type="text" id="lastName" placeholder="" value="" required="required" class="form-control" style="text-align: left;">
            <div class="invalid-feedback">
              <ya-tr-span data-index="17-0" data-translated="true" data-source-lang="ar" data-target-lang="ru" data-value=" يرجى إدخال اسم عائلة صحيح. " data-translation=" Пожалуйста, введите имя семьи справа. " data-type="trSpan"> Пожалуйста, введите имя семьи справа. </ya-tr-span>
            </div>
          </div>
          <div class="col-12">
            <label for="address" class="form-label">
              <ya-tr-span data-index="22-0" data-translated="true" data-source-lang="ar" data-target-lang="ru" data-value="العنوان" data-translation="Дата рождения" data-type="trSpan">Дата рождения</ya-tr-span>
            </label>
            <input type="date" id="address" placeholder="1234 Первая улица" required="required" class="form-control" style="text-align: left;">
          </div>
          <div class="col-12">
            <label for="address2" class="form-label">
              <ya-tr-span data-index="24-0" data-translated="true" data-source-lang="ar" data-target-lang="ru" data-value="عنوان 2 " data-translation="Адрес 2 " data-type="trSpan">Фото</ya-tr-span>
            </label>
            <input type="file" id="address2" class="form-control" style="text-align: left;">
            <div class="col-12">
              <label for="address2" class="form-label">
                <ya-tr-span data-index="24-0" data-translated="true" data-source-lang="ar" data-target-lang="ru" data-value="عنوان 2 " data-translation="Адрес 2 " data-type="trSpan">Пароль</ya-tr-span>
              </label>
              <input type="password" id="address2" class="form-control" style="text-align: left;">                      
            </div>
          </div>
        </div>
        <hr class="my-4">
        <button type="submit" class="w-100 btn btn-primary btn-lg">
          <ya-tr-span data-index="36-0" data-translated="true" data-source-lang="ar" data-target-lang="ru" data-value="الاستمرار بالدفع" data-translation="Продолжайте поддерживать" data-type="trSpan">Сохранить</ya-tr-span>
        </button>
      </form>
    </div>
  </div>
      
  
</template>

<script>
  export default {
    name: "v-make-profile",
    props: {},
    data() {
      return {}
    },
    computed: {}
  }
</script>

<style lang="scss">
  .v-make-profile{
    width: 80%;
    padding: 10%;
    margin: 16px;
    text-align: left;
    display: inline-block;
  }
</style>

