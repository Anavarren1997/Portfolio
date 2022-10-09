<template>
  <nav>
    <div class="left-menu">
      <router-link class="menu-item" to="/">A</router-link>
    </div>
    <div class="right-menu">
      <router-link class="menu-item" to="/about">ABOUT</router-link>
      <router-link class="menu-item" to="/experience">EXPERIENCE</router-link>
      <router-link class="menu-item" to="/projects">PROJECTS</router-link>
      <router-link class="menu-item" to="/stack">STACK</router-link>
      <router-link class="menu-item" to="/blog">BLOG</router-link>
      <router-link class="menu-item" to="/contact">CONTACT</router-link>
    </div>
  </nav>
</template>

<script></script>

<style scoped>
nav {
  width: 100%;
  height: 3rem;
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.right-menu {
  display: flex;
  align-items: center;
  justify-content: center;
  column-gap: 20px;
}

.menu-item {
  color: #8f9ba8;
  text-decoration: none;
  font-family: Biotif, sans-serif;
  font-size: 0.8rem;
}
</style>
