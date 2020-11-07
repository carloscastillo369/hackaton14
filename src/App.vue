<template>
  <div id="navbar">
    <router-link to="/" class="logo" href="#"> <img class="img-logo" src="@/assets/logo.png" alt=""> medika.</router-link>
    <div class="nav">
      <router-link to="/">Home</router-link>
      <router-link to="/about">About</router-link>
      <router-link to="/users">Users</router-link>
      <router-link to="/contact">Contact</router-link>
    </div>
  </div>
  <router-view/>
</template>

<script>
export default {
  
}
</script>

<style scoped>
#navbar {
  height: 70px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  font-size: 20px;
  padding: 0 30px;
  background: skyblue;

}

.logo:hover {
  text-decoration: none;
  font-weight: normal;
}

.img-logo {
  width: 30px;
  height: 30px;
}

img {
  width: 60px;
  height: 60px;
}

.nav {
  width: 500px;
  display: flex;
  justify-content: space-between;
}

a {
  text-decoration: none;
}

a:hover {
  color: blue;
  font-weight: bold;
  text-decoration: underline;
}
</style>