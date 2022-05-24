<template>
  <header class="p-3 bg-light text-dark">
    <div class="container">
      <div class="d-flex flex-wrap align-items-center justify-content-center justify-content-lg-start">
        <a href="/" class="d-flex align-items-center mb-2 mb-lg-0 text-dark text-decoration-none">
          <svg class="bi me-2" width="50" height="32"  aria-label="Bootstrap"><use xlink:href="#bootstrap"></use></svg>
        </a>

        <ul class="nav col-12 col-lg-auto me-lg-auto mb-2 justify-content-center mb-md-0">
          <li><a href="/" class="nav-link px-2 text-dark">Главная</a></li>
          <li><a href="/table_phys" class="nav-link px-2 text-dark">Таблица</a></li>
        </ul>

        <div class="text-end" >
          <a href="/login" button type="button" class="btn btn-outline-dark me-2">Войти</a>
        </div>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "MyHeader"
}
</script>

<style scoped>
.nav col-12 col-lg-auto me-lg-auto mb-2 justify-content-center mb-md-0{
  background-color: darkslateblue;
}
</style>