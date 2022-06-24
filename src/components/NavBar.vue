<template>
  <div class="nav-bar">
    <div class="header-top">

    </div>
    <div class="header-bot">
      <router-link
        to="/Home"
        class="font-general-medium block text-left text-lg font-medium text-primary-dark dark:text-ternary-light hover:text-indigo-600 dark:hover:text-indigo-300  sm:mx-4 mb-2 sm:py-2 "
        aria-label="Home">
        Home
      </router-link>
      <router-link
        to="/projects"
        class="font-general-medium block text-left text-lg font-medium text-primary-dark dark:text-ternary-light hover:text-indigo-600 dark:hover:text-indigo-300  sm:mx-4 mb-2 sm:py-2 "
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
  name: 'NavBar',
  props: {
    msg: String
  }
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
