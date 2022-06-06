<template>
  <div class="informacoes">
    <b-container id="contato">
      <b-row>
        <b-col cols="12" sm="12" md="12" lg="5" xl="6">
          <b-col cols="12" sm="8" md="6" lg="12" xl="12">
            <div class="conjunto">
              <div>
                <p class="frase-telefone">Telefones</p>
                <p class="celular">+55 (11) 3088-0757</p>
              </div>
              <div>
                <p class="frase-email">E-mail</p>
                <p class="email">renee@reneetrajar.com.br</p>
              </div>
              <div class="atendimento">
                <p>Atendimento Personalizado</p>
              </div>

              <div class="botao">
                <button class="botao-clique">Clique aqui!</button>
              </div>
            </div>
          </b-col>
        </b-col>

        <b-col cols="12" sm="" md="" lg="7" xl="6">
          <b-row>
            <b-col md="10" lg="10" xl="12">
              <div class="cont">
                <h3 class="contato">Contato</h3>
              </div>

              <b-col>
                <div class="span"></div>
              </b-col>
              <div class="nome">
                <b-form-input
                  class="input"
                  id="firstName"
                  placeholder="Nome"
                  type="text"
                ></b-form-input>
              </div>
            </b-col>
            <b-col md="10" lg="10" xl="12">
              <label class="label__text" for="firstName"> </label>
              <b-form-input
                class="input"
                id="firstName"
                placeholder="E-mail"
                type="text"
              ></b-form-input>
            </b-col>
          </b-row>

          <b-row>
            <b-col md="10" lg="10" xl="12">
              <label class="label__text___mensagem" for="firstName"> </label>
              <b-form-input
                class="input"
                id="firstName"
                placeholder="Mensagem"
                type="text"
              ></b-form-input>
            </b-col>
          </b-row>
          <b-row>
            <b-col md="10" lg="10" xl="12">
              <div class="enviar">
                <button class="enviar-bt">Enviar</button>
              </div>
            </b-col>
          </b-row>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>
<style scoped>
.informacoes {
  padding-bottom: 80px;
}
.frase-telefone {
  font-family: "Lato";
  font-style: normal;
  font-weight: 300;
  font-size: 18px;
  line-height: 22px;
  /* identical to box height */

  text-transform: uppercase;

  /* Azul 2 */

  color: #1c86a4;
}
.celular {
  font-family: "Lato";
  font-style: normal;
  font-weight: 300;
  font-size: 16px;
  line-height: 150.1%;
  /* identical to box height, or 24px */

  /* Gray 3 */

  color: #828282;
}
.frase-email {
  font-family: "Lato";
  font-style: normal;
  font-weight: 300;
  font-size: 18px;
  line-height: 22px;
  /* identical to box height */

  text-transform: uppercase;

  /* Azul 2 */

  color: #1c86a4;
}
.email {
  font-family: "Lato";
  font-style: normal;
  font-weight: 300;
  font-size: 16px;
  line-height: 19px;

  /* Gray 3 */

  color: #828282;
}
.input {
  border: 1.2px solid #1c86a4;
  border-radius: 3px;
}
.atendimento {
  font-family: "Lato";
  font-style: normal;
  font-size: 18px;
  font-weight: 300;

  /* identical to box height */

  text-transform: uppercase;

  /* Azul 2 */

  color: #1c86a4;
}
.botao-clique {
  font-size: 18px;
  line-height: 22px;

  border: 1px solid #1c86a4;
  background-color: white;
  border-radius: 2px;
  width: 270px;
  height: 50px;
  border-radius: 2px;
  text-align: center;

  /* Azul */

  color: #014561;
}
.botao-clique:hover {
  border: 1px solid #be9667;
  color: #be9667;
}
.cont {
  padding: 0 20px 5px 20px;
}
.span {
  border-bottom: 1px solid #70b0c4;
  height: 10px;
  width: 53px;
}
.nome {
  padding-top: 20px;
}
.contato {
  /* Títulos */

  font-family: "Cormorant";
  font-style: normal;
  font-weight: 300;
  font-size: 38px;
  line-height: 46px;
  /* identical to box height */

  display: flex;
  align-items: center;
  text-align: center;

  /* Azul 2 */

  color: #1c86a4;
}
.enviar {
  padding-top: 20px;
}
.enviar-bt {
  border: none;
  width: 100%;
  height: 50px;
  background: #014561;

  border-radius: 2px;
  color: white;
  font-weight: bold;
  font-size: 16px;
}
.enviar-bt:hover {
  background: #00648c;
  transition: 0.5s;
}
</style>
<script>
</script>