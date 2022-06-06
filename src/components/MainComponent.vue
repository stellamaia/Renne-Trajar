<template>
  <div class="main">
    <div class="conteudo">
      <b-row>
        <img
          class="metodos-imagem"
          src="../assets/photo-main.png"
          alt="estilista"
        />

        <div class="conjunto-infos-um">
          <div class="titulo">
            <p>Renne Trajar</p>
          </div>
          <div class="span"></div>
          <div class="sub-titulo">
            <p>
              Com mais de 35 anos de experiência em camisas, calças e ternos sob
              medida, possuímos <br />profissionais experientes e altamente
              qualificados.<br />
              Cada cliente tem seu molde exclusivamente desenvolvido para seu
              biotipo através das<br />
              medidas tiradas pelo próprio Sr. Renee, no escritório ou
              residência do cliente.
            </p>
          </div>
          <div class="sub-titulo-2">
            <p>
              “Nosso objetivo é superar a expectativa do cliente
              proporcionando-lhe satisfação <br />
              ao usar nossos produtos, aliado a um relacionamento franco e
              honesto,<br />
              valorizando o ser humano.”
            </p>
          </div>
          <p class="frase">Renne Trajar</p>
          <div class="bt">
            <button class="botao">Agende uma visita!</button>
          </div>
        </div>

        <img class="aspas-img" src="../assets/aspas.png" />
      </b-row>
    </div>
  </div>
</template>

<script>
export default {
  name: "MainComponent",
};
</script>

<style scoped>
.conteudo {
  padding: 20px 0px 20px 60px;
}

.botao {
  /* Azul */
  width: 297px;
  height: 50px;
  border-radius: 2px;
  background: #014561;

  font-style: normal;
  font-weight: 100;
  font-size: 20px;

  /* identical to box height */
  text-align: center;
  text-transform: uppercase;
  color: #e5e5e5;
}

.conjunto-infos-um {
  padding: 0px 0px 0 30px;
}

.titulo {
  /* Títulos */

  font-family: "Cormorant";
  font-style: normal;
  font-weight: 300;
  font-size: 38px;

  display: flex;
  align-items: center;
  text-align: center;

  /* Azul */

  color: #014561;
}
.span {
  padding: 10px 60px 0 9px;
  border-bottom: 1px solid #70b0c4;
  width: 20px;
}
.sub-titulo {
  font-family: "Lato";
  font-style: normal;
  font-weight: 300;
  font-size: 22px;
  padding-top: 50px;
  /* or 27px */

  /* Gray 1 */

  color: #b1b1b1;
}
.sub-titulo-2 {
  font-family: "Cormorant";
  font-style: italic;
  font-weight: 400;
  font-size: 22px;

  /* or 34px */

  /* Azul 2 */

  color: #1c86a4;
}
.botao {
  /* Azul */
  width: 297px;
  height: 50px;
  border-radius: 2px;
  background: #014561;

  font-style: normal;
  font-weight: 100;
  font-size: 20px;

  /* identical to box height */
  text-align: center;
  text-transform: uppercase;
  color: #e5e5e5;
  border: none;
}
.botao:hover {
  background: #01374e;
  transition: 0.5s;
}
.aspas-img {
  z-index: 2;
  top: 150px;
  right: 90px;
  position: relative;
  height: 120px;
}
.frase {
  font-family: "Cormorant";
  font-style: normal;
  font-weight: 500;
  font-size: 20px;
  line-height: 141.3%;
  /* or 28px */

  /* Gray 3 */

  color: #828282;
}
.linha-img {
  background-color: rgba(157, 157, 157, 0.201);
}
@media screen and (min-width: 320px) and (max-width: 480px) {
  .metodos-imagem {
    width: 300px;
  }
  .conteudo {
    padding: 10px 10px 0 40px;
  }
  .conjunto-infos-um {
    padding: 10px 10px 0 10px;
  }
}
@media screen and (min-width: 481px) and (max-width: 768px) {
  .conjunto-infos-um {
    padding: 60px 10px 0 10px;
  }
}
@media screen and (min-width: 769px) and (max-width: 1024px) {
  .conteudo {
    padding: 10px 10px 0 40px;
  }

  .conjunto-infos-um {
    padding: 0px 10px 0 30px;
  }
}
@media screen and (min-width: 1025px) and (max-width: 1301px) {
}
@media screen and (min-width: 1302px) and (max-width: 1500px) {
  .conjunto-infos-um {
    padding: 0px 120px 0 90px;
  }
  .frase {
    padding: 0 20px 0 300px;
  }
}
@media screen and (min-width: 1501px) {
  .conjunto-infos-um {
    padding: 0px 120px 0 170px;
  }
  .frase {
    padding: 0 0 0 500px;
  }
}
</style>