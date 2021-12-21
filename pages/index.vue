<template>
  <div>
  <b-navbar toggleable="lg" type="dark" variant="info">
    <b-navbar-brand href="#">ICGE</b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav>
        <b-nav-item href="#">Beranda</b-nav-item>
        <b-nav-item href="#">Galeri</b-nav-item>
        <b-nav-item href="#">Publikasi</b-nav-item>
        <b-nav-item href="#">Arsip</b-nav-item>
      </b-navbar-nav>

      <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto">
        

        <b-nav-item-dropdown text="Lang" right>
          <b-dropdown-item href="#">EN</b-dropdown-item>
          <b-dropdown-item href="#">ES</b-dropdown-item>
          <b-dropdown-item href="#">RU</b-dropdown-item>
          <b-dropdown-item href="#">FA</b-dropdown-item>
        </b-nav-item-dropdown>
        
        <b-navbar-nav>
        <b-nav-item href="#">Daftar</b-nav-item>
        </b-navbar-nav>

      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</div>
</template>

<style>
  body{
    font-family: sans-serif;
    margin: 4%;
  }
  .navbar{
    border-radius : 25px;
  }
</style>

<script>
export default {
  name: 'IndexPage'
}
</script>
