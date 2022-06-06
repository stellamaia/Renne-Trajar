<template>
  <div>
    <div class="header-content">
      <h3 class="frase-um">Elegante é ter um</h3>
      <h1 class="frase-dois">Alfaiate</h1>

      <h3 class="frase-tres">para chamar de seu.</h3>

      <p class="paragrafo-um">
        Compre hoje,
        <span class="paragrafo-dois">
          pague em até 3x <br />
          com 12% de desconto
        </span>
        e tenha<br />
        10 meses para confeccionar!
      </p>
      <div class="botao">
        <button class="botao-orcamento">Faça já um orçamento</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HeaderComponent",
  props: {
    msg: String,
  },
};
</script>
<style scoped>
.header-content {
  padding: 40px 60px 0 120px;
}
.frase-um {
  padding-top: 20px;

  font-family: "Playfair Display";
  font-style: italic;
  font-weight: 400;
  font-size: 2rem;

  /* identical to box height */
  color: #be9667;
}
.frase-dois {
  /* Alfaiate */

  font-family: "Playfair Display";
  font-style: normal;
  font-weight: 400;
  font-size: 60px;
  font-size: 90px;
  /* identical to box height */

  text-transform: uppercase;

  color: rgba(2, 75, 104, 0.68);
}

.frase-tres {
  /* para chamar de seu. */
  width: 420px;
  text-align: end;
  line-height: 20px;
  font-family: "Playfair Display";
  font-style: italic;
  font-weight: 400;
  font-size: 2rem;

  color: #be9667;
}
.paragrafo-um {
  /* COMPRE HOJE, PAGUE EM ATÉ 3X COM 12% DE DESCONTO E TENHA 10 MESES PARA CONFECCIONAR! */

  font-style: normal;
  font-weight: 100;
  font-size: 24px;
  padding-top: 80px;
  /* or 31px */
  text-transform: uppercase;
  color: #e5e5e5;
}
.paragrafo-dois {
  font-weight: 400;
}

.botao-orcamento {
  /* Azul */
  width: 297px;
  height: 50px;
  border-radius: 2px;
  background: #014561;
  border: none;
  font-style: normal;
  font-weight: 100;
  font-size: 20px;

  /* identical to box height */
  text-align: center;
  text-transform: uppercase;
  color: #e5e5e5;
}
.botao-orcamento:hover {
  transition: 0.5s;
  background: #01374e;
}
</style>
