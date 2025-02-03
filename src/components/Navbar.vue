<template>
  <nav>
    <div class="logo">
      <a href="#home">
        <img :src="logoUrl" alt="My Logo" class="navbar-logo"/> 
      </a>
    </div>
    <div class="nav-list">
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#education">Education & Experience</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </div>
  </nav>
</template>
<script>
export default {
    name: 'NavBar',
    data() {
      return {
        logoUrl: 'https://github.com/candice-dk3/vueProjectImages/blob/main/CK.png?raw=true'
      };
    },
}
</script>
<style scoped>
nav {
  background-color: #B691C2C9;
  position: fixed;
  width: 100%;
  height: 115px;
}
nav a {
  font-weight: bold;
  color: #fff;
  text-transform: uppercase;
  text-decoration: none;
  font-size: 24px;
  font-weight: 300;
  margin-top: 40px;
}
nav a:hover{
    color: #FFF500;
    transition: color 0.3s ease-in-out, transform 0.2s ease-in-out;
}
nav a.active {
  color: #FFF500;
}
.nav-list{
  display: flex;
  gap: 20px;
  justify-content: end;
  margin-right: 30px;
}
.navbar-logo {
  width: 140px;
  position: fixed;
  left: 20px;
  top: -20px;
}

</style>