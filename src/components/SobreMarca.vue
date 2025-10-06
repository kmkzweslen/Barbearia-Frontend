<template>
  <section class="sobre-marca">
    <div class="grid">
      <div class="col-left">
        <h2>SOBRE SUA MARCA</h2>
        <div class="icon-g">🪒</div>
        <p>
          Mais do que uma barbearia, A Navalha de Ouro é um santuário para o homem moderno que valoriza a tradição e a precisão. Em nosso ambiente, o aroma de loções clássicas se mistura ao som suave do blues, criando uma atmosfera onde cada cliente pode relaxar e se desconectar da correria do dia a dia. 
        </p>
      </div>
      <div class="col-right">
        <div class="img-placeholder">[ IMAGEM ]</div>
      </div>
    </div>
  </section>
  <section class="equipe">
    <div class="grid">
      <div class="col-left">
        <div class="img-equipe">[ IMAGEM ]</div>
      </div>
      <div class="col-right-t">
        <h2>EQUIPE</h2>
        <div class="icon-t">✂️</div>
        <p>
          Nossos barbeiros, verdadeiros artesãos da navalha e da tesoura, dominam tanto os cortes clássicos quanto as tendências contemporâneas...
        </p>
      </div>
    </div>
  </section>
</template>
<style scoped>
.sobre-marca {
  background: url('@/assets/img-sobre-marca.png');
  color: #fff;
  padding: 40px 0;
}
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
.col-left { max-width: 50%; }
.col-right {
  display: flex;
  flex-direction: column;
  align-items: end;
}
.img-placeholder {
  width: 350px;
  height: 350px;
  background: #222;
  color: #fff;
  display: flex;
  align-items: center;
  justify-content: center;
  border: 3px solid #4169E1;
  margin-bottom: 20px;
}
.img-equipe {
  width: 350px;
  height: 350px;
  background: #222;
  color: #fff;
  display: flex;
  align-items: center;
  justify-content: center;
  border: 3px solid #db101a;
  margin-top: 20px;
  margin-bottom: 20px;
}
.col-right-t { max-width: 60%; }
.icon-g { font-size: 2rem; margin-bottom: 14px; }
.icon-t{ font-size: 2rem; margin-bottom: 14px; }
</style>
