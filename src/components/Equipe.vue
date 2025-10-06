<template>
  <section class="equipe">
    <div class="grid">
      <div class="col-left">
        <div class="img-placeholder">[ IMAGEM ]</div>
      </div>
      <div class="col-right">
        <h2>EQUIPE</h2>
        <div class="icon">✂️</div>
        <p>
          Nossos barbeiros, verdadeiros artesãos da navalha e da tesoura, dominam tanto os cortes clássicos quanto as tendências contemporâneas...
        </p>
      </div>
    </div>
  </section>
</template>
<style scoped>
.equipe {
  background: #0e0e0e;
  color: #fff;
  padding: 40px 0;
}
.grid {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
}
.col-left {
  width: 160px;
  height: 160px;
  background: #222;
  color: #fff;
  display: flex;
  align-items: center;
  justify-content: center;
  margin-right: 40px;
}
.img-placeholder {
  width: 200px;
  height: 220px;
  background: #333;
  color: #fff;
  display: flex;
  align-items: center;
  justify-content: center;
}
.col-right { max-width: 60%; }
.icon { font-size: 2rem; margin-bottom: 14px; }
</style>
