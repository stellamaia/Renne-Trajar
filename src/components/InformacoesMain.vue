<template>
  <div id="empresa">
    <b-row>
      <div class="conteudo-dois">
        <b-col cols="12" sm="12" md="12" lg="12" xl="7">
          <div class="descricao">
            <p>
              “Faço roupas com o Renee Trajar há mais de duas décadas, o
              <br />serviço é impecável em todos os detalhes, desde a costura ao
              <br />
              caimento. O Renee tem uma equipe de mestre!”
            </p>
          </div>

          <div class="paragrafo-nelson">
            <h1>Nelson Garey</h1>
          </div>
          <div>
            <h3 class="paragrafo-infos">
              Advogado | Nelson Garey Advogados Associados
            </h3>
          </div>
        </b-col>
      </div>
    </b-row>
  </div>
</template>
<style scoped>
.conteudo-dois {
  background: no-repeat center/cover url("../assets/fundo-card.png");
  height: 100%;
  width: 100%;
}

.descricao {
  font-family: "Lato";
  font-style: normal;
  font-weight: 100;
  font-size: 24px;
  padding-top: 70px;
  line-height: 25px;
  padding-bottom: 25px;
  /* or 34px */

  text-align: center;

  /* Gray 3 */

  color: #828282;
}
.paragrafo-nelson {
  font-family: "Cormorant";
  font-style: italic;

  font-size: 22px;

  /* identical to box height, or 40px */

  text-align: center;

  /* Azul */

  color: #014561;
}
.paragrafo-infos {
  font-family: "Lato";
  font-style: normal;
  font-weight: 300;
  font-size: 20px;

  /* or 28px */

  text-align: center;

  /* Dourado */

  color: #be9667;
}
.card-img-um {
  position: relative;
  left: 73%;
}
.card-img-dois {
  z-index: -1;
  position: relative;
  left: 68%;
}
@media screen and (min-width: 481px) and (max-width: 768px) {
  .conteudo-dois {
    width: 100%;
  }
  .descricao {
    color: black;
    text-align: start;
    padding: 90px 0 0 50px;
  }
}
@media screen and (min-width: 769px) and (max-width: 1024px) {
  .descricao {
    text-align: start;
    padding: 90px 0 0 50px;
  }
  .paragrafo-nelson,
  .paragrafo-infos {
    text-align: start;
    padding: 0 0 0 50px;
  }
}
@media screen and (min-width: 1025px) and (max-width: 1200px) {
  .descricao {
    text-align: start;
    padding: 90px 0px 0 90px;
  }
  .paragrafo-nelson {
    text-align: start;
    padding: 10px 0px 0 90px;
  }
  .paragrafo-infos {
    text-align: start;
    padding: 0px 0px 0 90px;
  }
}
@media screen and (min-width: 1201px) {
  .conteudo-dois {
    height: 590px;
    padding-top: 100px;
  }
}
</style>