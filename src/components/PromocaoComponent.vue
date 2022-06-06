<template>
  <div class="conteudo">
    <div class="img-promocao-1">
      <div class="img-promocao-2">
        <div class="principal">
          <b-container>
            <b-row>
              <b-col cols="12" sm="12" md="6" lg="7" xl="8">
                <p class="titulo-2">Condição Imperdível</p>
                <p class="sub-titulo">Compre Hoje e garanta</p>
                <div class="informacoes">
                  <p>
                    <span class="linha">-</span> 12% de desconto e pagamento em
                    até
                    <span class="informacoes-bold">3x sem juros;</span>
                  </p>
                  <p>
                    <span class="linha">-</span> Até
                    <span class="informacoes-bold">10 meses</span>para
                    confeccionar sua roupa. Não se preocupe se<br />
                    suas medidas aumentaram ou diminuíram, estará sempre
                    elegante:
                  </p>
                  <p>
                    <span class="linha">-</span> Condição muito especial
                    por<span class="informacoes-bold"> tempo limitado;</span>
                  </p>
                  <p>
                    <span class="linha">-</span>Poder presentear alguém com uma
                    roupa de alta costura, exclusiva.
                  </p>
                </div>
                <button class="botao">Garanta essa condição especial!</button>
              </b-col>
              <b-col cols="" sm="" md="5" lg="5" xl="4">
                <img class="img-promocao" src="../assets/promocao-img.png" />
              </b-col>
            </b-row>
          </b-container>
        </div>
      </div>
    </div>
  </div>
</template>
<style scoped>
.titulo-2 {
  font-family: "Cormorant";
  font-style: normal;
  font-weight: 400;
  font-size: 53px;
  line-height: 64px;
  padding-bottom: 20px;
  text-transform: uppercase;
  color: #be9667;
  text-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
}
.linha {
  color: #be9667;
}
.principal {
  padding-top: 60px;
  padding-bottom: 60px;
}
.sub-titulo {
  font-family: "Cormorant";
  font-style: italic;
  font-weight: 400;
  font-size: 30px;
  line-height: 36px;

  color: #be9667;

  text-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
}
.informacoes {
  font-family: "Lato";
  font-style: normal;
  font-weight: 300;
  font-size: 22px;
  line-height: 26px;
  padding-bottom: 40px;
  color: #c4c4c4;
}
.informacoes-bold {
  font-weight: bold;
}
.img-promocao {
  padding: 0 100px 0 70px;
}
.img-promocao-1 {
  background: no-repeat center/cover url("../assets/banner-promocao2.png");
}
.img-promocao-2 {
  background: linear-gradient(
    180deg,
    rgba(2, 22, 31, 0.972) 0%,
    rgba(2, 34, 47, 0.966) 0.17%
  );
}
.botao {
  background: #be9667;

  font-size: 18px;
  color: #e0e0e0;
  width: 330px;
  height: 55px;
  border-radius: 2px;
  border: none;
}
.botao:hover {
  background: #616161;
  transition: 0.5s;
}
</style>
