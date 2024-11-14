<script setup lang="ts">
definePageMeta({
    layout: 'dashboard'
})
</script>

<template>
    <div class="dashboard-layout">
  
        
      <div class="main-content">
       
        <header class="dashboard-header">
          <h1>Dashboard</h1>
          <div class="user-info">
            <p>Welcome, User!</p>
          </div>
        </header>
  
      
        <div class="dashboard-content">
            <div class="card">
            <h3>The Coola Guy Team Startup Profits</h3>
            <p>$100,000,000</p>
          </div>
          <div class="card">
            <h3>Revenue</h3>
            <p>$15,000</p>
          </div>
          <div class="card">
            <h3>Active Users</h3>
            <p>1,500</p>
          </div>
          <div class="card">
            <h3>New Orders</h3>
            <p>120</p>
          </div>
        </div>
      </div>
    </div>
  </template>
  
<style scoped>

.dashboard-layout {
  display: flex;
  height: 100vh;
  font-family: Arial, sans-serif;
}


.sidebar {
  width: 250px;
  background-color: #2e3b4e;
  color: white;
  padding: 20px;
  box-sizing: border-box;
}

.sidebar h2 {
  margin-bottom: 20px;
}

.sidebar nav ul {
  list-style: none;
  padding: 0;
}

.sidebar nav ul li {
  margin-bottom: 10px;
}

.sidebar nav ul li a {
  color: white;
  text-decoration: none;
  font-weight: bold;
}


.main-content {
  flex: 1;
  display: flex;
  flex-direction: column;
  background-color: #f5f7fa;
}


.dashboard-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px;
  background-color: #1378f3;
  color: white;
}

.dashboard-header h1 {
  margin: 0;
}

.dashboard-header .user-info p {
  margin: 0;
}


.dashboard-content {
  display: flex;
  gap: 20px;
  padding: 20px;
  flex-wrap: wrap;
}


.card {
  background-color: #dd8787;
  padding: 20px;
  flex: 1;
  flex-direction: justify-content;
  align-content: center;
  border-radius: 8px;
  box-shadow: 0 4px 8px rgba(209, 205, 205, 0.1);
  width: 200px;
  text-align: center;
}

.card h3 {
  margin: 0 0 10px;
}

.card p {
  margin: 0;
  font-size: 1.2em;
  font-weight: bold;
}
</style>

  