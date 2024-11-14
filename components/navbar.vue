<template>
  <nav class="navbar">
    <div class="logo">
      <svg width="50" height="50" viewBox="0 0 50 50">
        <!-- Graduation Cap -->
        <path d="M25 10L5 20L25 30L45 20L25 10Z" fill="#2196F3" />
        <path
          d="M15 22.5V32.5C15 35.5 25 40 25 40C25 40 35 35.5 35 32.5V22.5"
          fill="#1976D2" />
        <!-- Tassel -->
        <path d="M35 21.5V33L38 35V23.5L35 21.5Z" fill="#1565C0" />
      </svg>
    </div>
    <div>
      <div class="menu">
        <NuxtLink to="/dashboard">Dashboard</NuxtLink>
        <NuxtLink to="/contacts">Contact</NuxtLink>
        <div class="menu-item">
          <a href="#login">Account</a>
          <div class="dropdown">
            <NuxtLink to="/login">Login</NuxtLink>
            <NuxtLink to="/register">Register</NuxtLink>
          </div>
        </div>
      </div>
    </div>
  </nav>
</template>
<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
}

.navbar {
  display: flex;
  background-color: #333;
  padding: 10px 20px;
  justify-content: space-between;
  align-items: center;
}

.navbar a {
  color: white;
  text-decoration: none;
  padding: 10px 15px;
  display: inline-block;
}

.navbar a:hover {
  background-color: #555;
}

.navbar .menu {
  display: flex;
  align-items: center;
}

.navbar .menu-item {
  position: relative;
}

.navbar .menu .dropdown {
  position: absolute;
  top: 100%;
  left: 0;
  background-color: #333;
  display: none;
  flex-direction: column;
}

.navbar .menu-item:hover .dropdown {
  display: flex;
}

.navbar .dropdown a {
  padding: 10px;
  text-align: left;
  width: 100px;
}

/* Responsive styling */
@media (max-width: 600px) {
  .navbar {
    flex-direction: column;
  }

  .navbar .menu {
    flex-direction: column;
    width: 100%;
  }

  .navbar .menu-item,
  .navbar .dropdown a {
    width: 100%;
    text-align: center;
  }
}
.logo {
  display: flex;
  align-items: center;
  padding: 5px;
}

.logo svg {
  transition: transform 0.3s ease;
}

.logo svg:hover {
  transform: scale(1.1);
}
</style>
