<script setup>
</script>

<template>
  <nav class="navbar navbar-dark bg-dark fixed-top">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">Nginx-PlateForm</a>
    <div class ="searchBox">
      <form class="d-flex" role="search">
        <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
        <button class="btn btn-outline-success" type="submit">搜索</button>
      </form>
    </div>
  </div>
</nav>
</template>

<style scoped>
.searchBox{
  float:right;
  white-space:nowrap;
}
</style>
