<template>
  <header class="header">
    <nav>
      <ul class="nav-list">
        <li><a href="#" class="active">HOME</a></li>
        <li><a href="#">NOSSA MARCA</a></li>
        <li><a href="#">BARBA & CABELO</a></li>
        <li><a href="#">AGENDE</a></li>
      </ul>
      <div class="logo-placeholder"></div>
    </nav>
  </header>
</template>
<style scoped>
.header {
  background: #1a1a1a;
  padding: 16px 0;
  color: #fff;
  display: flex;
  justify-content: center;
  align-items: center;
}
.nav-list {
  display: flex;
  gap: 32px;
  list-style: none;
}
.nav-list .active {
  color: #DAA520;
  font-weight: 700;
}
.logo-placeholder {
  background: url('src/assets/logo.png') center/contain no-repeat;
  margin-left: 48px;
  font-size: 2rem;
  color: #fff;
}
</style>
