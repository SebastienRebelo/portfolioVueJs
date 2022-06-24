<template>
  <div class="nav-bar">
    <div class="header-top">
       
    </div>
    <div class="header-bot">
      <router-link
        to="/"
        class=""
        aria-label="Home">
        Home
      </router-link>
      <router-link
        to="/projects"
        class=""
        aria-label="Projects">
        Projects
      </router-link>
      <router-link
        to="/about"
        class=""
        aria-label="About Me">
        About Me
      </router-link>
		  <router-link
        to="/contact"
        class=""
        aria-label="Contact">
        Contact
      </router-link>
    </div>
  </div>
</template>

<script>
export default {
  name: 'NavBar'
}
</script>

<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
