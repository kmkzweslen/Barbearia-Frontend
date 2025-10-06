<template>
  <section class="hero">
    <div class="hero-background"></div>
    <div class="hero-content">
      <div class="hero-logo">△ LOGO</div>
      <div class="hero-arrow left">‹</div>
      <div class="hero-arrow right">›</div>
    </div>
  </section>
</template>
<style scoped>
.hero {
  background: #000;
  height: 340px;
  position: relative;
  display: flex;
  align-items: center;
  justify-content: center;
}
.hero-background {
  width: 100%;
  height: 100%;
  background: #222;
  position: absolute;
  top: 0; left: 0;
  opacity: 0.6;
}
.hero-content {
  position: relative;
  z-index: 2;
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
}
.hero-logo {
  color: #fff;
  font-size: 3rem;
  margin: auto;
}
.hero-arrow {
  font-size: 2.5rem;
  color: #DAA520;
  cursor: pointer;
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
}
.left { left: 20px; }
.right { right: 20px; }
</style>
