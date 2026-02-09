<template>
  <header class="top-bar">
    <div class="header-content">
      <h1 class="logo">Algoritmos</h1>
      <nav class="navigation">
        <!-- todo -->
      </nav>
    </div>
  </header>
</template>

<style scoped>
.top-bar {
  background-color: #ffffff;
  border-bottom: 1px solid #eaeaea;
  width: 100%;
  position: sticky;
  top: 0;
  z-index: 1000;
  box-shadow: 0 2px 4px rgba(0,0,0,0.02);
}

.header-content {
  max-width: 1200px;
  margin: 0 auto;
  padding: 1rem 2rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: 60px;
}

.logo {
  font-family: 'Georgia', serif;
  font-size: 1.5rem;
  color: #2c3e50;
  font-weight: bold;
  margin: 0;
  letter-spacing: -0.5px;
}
</style>
