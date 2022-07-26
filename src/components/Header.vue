<template>
  <div class="header">
      <img src="@/assets/header/logo.png" alt="whiteyorkie-logo" srcset="">
      <nav>
          <router-link to="/">Home</router-link>
          <router-link to="/contato">Contato</router-link>
          <router-link to="/blog">Blog</router-link>
          <router-link to="/sobre">Sobre</router-link>
      </nav>
  </div>
</template>

<script>
export default {
    name: 'Header',
}
</script>

<style scoped>
.header {
    background: #9E2B20;
    box-shadow: 0px 5px 50px 20px rgba(0, 0, 0, 0.5);

    width: 100%;
    height: 100px;

    display: flex;
    align-items: center;
    justify-content: space-between;

    font-family: montserrat;
    font-weight: 600;
}
img {margin-left: 85px;}
nav {margin-right: 85px;}
a {
    padding: 30px;
    text-decoration: none;
    color: white;
}
nav a.router-link-exact-active {
  font-weight: 800;
}
</style>