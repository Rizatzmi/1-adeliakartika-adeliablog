<template>
  <header>
    <div class="container">
      <nav>
        <a href="#">
          <img src="../assets/logo.png" alt="Logo" width="100" />
        </a>
        <ul>
          <li><router-link to="/">Home</router-link></li>
          <li><a href="#">Blogs</a></li>
          <li><router-link to="/about">About</router-link></li>
          <li><a href="#">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<script>
export default {};
</script>

<style scoped>
header {
  background-color: #212D44;
  color: #EBECED;
  margin-bottom: 100px;
}

nav {
  display: flex;
  flex-direction: row;
  min-height: 70px;
  justify-content: space-between;
  align-items: center;
}

nav ul {
  list-style: none;
  display: flex;
  flex-direction: row;
}

nav ul li {
  margin: 2px 20px;
}
</style>
