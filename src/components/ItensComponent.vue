<template>
  <div class="itens-component">
    <b-container id="camisaria">
      <div class="conjunto-infos-um">
        <b-row>
          <b-col cols="12" sm="12" md="12" lg="8" xl="6">
            <img class="img-um" src="../assets/item1.png" alt="Camisa" />
          </b-col>
          <b-col class="itens" cols="12" sm="12" md="" lg="4" xl="4">
            <div class="titulo">Camisaria</div>
            <div class="sub-titulo">- confeccionadas artesanalmente</div>
            <div class="sub-titulo-2">
              <ul>
                <li>100% Algodão</li>
                <li>Monograma</li>
                <li>Slim</li>
              </ul>
              <ul>
                <li>Nacionais e Importadas</li>
                <li>Tradicionais e Esportivas</li>
                <li>Casamentos</li>
              </ul>
            </div>
            <button class="botao">Quero um orçamento</button>
          </b-col>
        </b-row>
      </div>
    </b-container>
    <div class="padd">
      <b-container id="camisaria">
        <div class="conjunto-infos-dois">
          <b-row>
            <b-col class="itens" cols="12" sm="12" md="12" lg="8" xl="6">
              <div class="titulo">Camisaria</div>
              <div class="sub-titulo">- confeccionadas artesanalmente</div>
              <div class="sub-titulo-2">
                <ul>
                  <li>100% Algodão</li>
                  <li>Monograma</li>
                  <li>Slim</li>
                </ul>
                <ul>
                  <li>Nacionais e Importadas</li>
                  <li>Tradicionais e Esportivas</li>
                  <li>Casamentos</li>
                </ul>
              </div>
              <button class="botao">Quero um orçamento</button>
            </b-col>
            <b-col cols="" sm="" md="5" lg="5" xl="4">
              <img class="img-dois" src="../assets/item2.png" alt="Camisa" />
            </b-col>
          </b-row>
        </div>
      </b-container>
    </div>
  </div>
</template>
<style scoped>
.itens {
  padding: 30px 0 0 0;
}
.itens-2 {
  padding: 50px 0 0 0;
}
.img-um {
  height: 500px;
  bottom: -60px;
  right: 10px;
  z-index: 1;
  position: absolute;
}
.img-dois {
  height: 500px;
  top: -40px;
  left: 30px;
  z-index: 1;
  position: absolute;
}

.titulo {
  font-family: "Cormorant";
  font-style: normal;
  font-weight: 300;
  font-size: 62px;
  /* identical to box height */
  text-transform: uppercase;
  /* Azul */

  color: #014561;
}
.conjunto-infos-um {
  border: 1px solid rgb(216, 216, 216);
  padding-bottom: 20px;
  margin: 40px 0 20px 0;
}
.padd {
  padding-top: 50px;
}
.conjunto-infos-dois {
  border: 1px solid rgb(216, 216, 216);

  margin: 40px 0 20px 0;
}

.sub-titulo {
  font-family: "Lato";
  font-style: normal;
  font-weight: 400;
  font-size: 16px;
  text-transform: uppercase;
  color: #c4c4c4;
}
.sub-titulo-2 {
  font-family: "Cormorant";
  font-style: italic;
  font-weight: 400;
  font-size: 24px;
  line-height: 29px;

  color: #727272;
}
.botao {
  /* Azul */

  background: #014561;
  border-radius: 2px;
  font-size: 18px;
  width: 330px;
  height: 55px;
  border-radius: 2px;
  border: none;
  color: #e5e5e5;
}

.botao:hover {
  background: #01374e;
  transition: 0.5s;
}
@media screen and (min-width: 320px) and (max-width: 1200px) {
  .img-um,
  .img-dois {
    z-index: 0;
    position: relative;
    padding: 0;
    bottom: 0;
    top: 30px;
    right: 0;
  }
  .titulo {
    text-align: start;
  }
  .conjunto-infos-um,
  .conjunto-infos-dois {
    padding-top: 20px;
    padding-bottom: 0px;
    border: none;

    margin: 0;
  }

  .itens-component {
    height: 100%;
  }
}
</style>