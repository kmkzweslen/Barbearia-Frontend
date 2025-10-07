<template>
  <section class="meio">
    <div class="grid-meio">
      <div class="marca">
        <h2>SOBRE SUA MARCA</h2>
        <p>Mais do que uma barbearia, A Navalha de Ouro é um santuário para o homem moderno que valoriza a tradição e a precisão. Em nosso ambiente, o aroma de loções clássicas se mistura ao som suave do blues, criando uma atmosfera onde cada cliente pode relaxar e se desconectar da correria do dia a dia.</p>
      </div>
      <div class="espaco"></div>
      <div class="equipe">
        <h2>EQUIPE</h2>
        <p> Nossos barbeiros, verdadeiros artesãos da navalha e da tesoura, dominam tanto os cortes clássicos quanto as tendências contemporâneas, garantindo um serviço impecável e personalizado. Na Navalha de Ouro, cada barba é uma escultura e cada corte de cabelo é uma obra de arte.</p>
      </div>
    </div>
  </section>
</template>
<style scoped>
.meio{
  background: url('src/assets/barber.png') center/cover no-repeat;
  color: #fff;
  padding: 40px 0;
  display: flex;
  justify-content: center;
}
.grid-meio {
  width: 90%;
  max-width: 1100px;
  min-height: 500px;
  background: transparent;
  display: grid;
  grid-template-columns: 1fr 1fr;
  grid-template-rows: 1fr 1fr;
  gap: 0;
  position: relative;
}
.marca {
  grid-column: 1/2;
  grid-row: 1/2;
  background: #242424;
}
.equipe {
  grid-column: 2 / 3;
  grid-row: 2 / 3;
  background: #242424;
}

</style>