<template>
  <div class="qualidade-component">
    <b-row class="text-center">
      <b-col cols="4">
        <img src="../assets/vector1.png" alt="" />
        <div class="separacao">
          <h6 class="titulo">Qualidade</h6>
          <p class="descricao">Camisaria e Alfaiataria 100% artesanal.</p>
        </div>
      </b-col>
      <b-col cols="4">
        <img src="../assets/vector2.png" alt="" />
        <div class="separacao">
          <h6 class="titulo">Confiança</h6>
          <p class="descricao">
            Atendimento personalizado no escritório ou residência.
          </p>
        </div>
      </b-col>
      <b-col cols="4">
        <img src="../assets/vector3.png" alt="" />
        <div class="separacao">
          <h6 class="titulo">Experiência</h6>
          <p class="descricao">
            Tradição e modernidade proporcionando elegância.
          </p>
        </div>
      </b-col>
    </b-row>
  </div>
</template>
<style scoped>
.titulo {
  font-family: "Cormorant";
  font-style: normal;
  font-weight: 600;
  font-size: 24px;
  line-height: 29px;
  /* identical to box height */

  text-align: center;
  text-transform: uppercase;

  /* Azul 2 */

  color: #1c86a4;
}
.separacao {
  border-left: 1px solid rgb(217, 217, 217);
}
.descricao {
  color: #727272;

  font-family: "Lato";
  font-style: normal;
  font-weight: 300;
  font-size: 14px;
}
.qualidade-component {
  padding: 70px 0 70px 0;
}
</style>