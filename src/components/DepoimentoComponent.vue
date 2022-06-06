<template>
  <div id="depoimentos">
    <div class="depoimentos">
      <!--depoimentos 1 desktop -->
      <div class="home-page">
        <b-carousel
          class="carousel-fade"
          id="mainCarousel"
          :interval="4000"
          indicators
          controls
        >
          <b-carousel-slide class="slide">
            <div class="cont">
              <h5 class="titulo">Depoimentos</h5>
              <img src="../assets/depoimento-1.png" alt="" />
              <div class="descricao">
                <p>
                  “Sou cliente do Renee há uns 12 anos. Nosso primeiro contato
                  foi por intermédio de
                </p>
                <p>
                  meu pai, que já tem uma história de décadas com o querido
                  Renee.
                </p>
                <p>
                  O excelente atendimento antes e pós venda e a alta qualidade
                  dos materiais usados
                </p>
                <p>
                  colocam a Renee Trajar em um patamar acima dos demais do
                  ramo.”
                </p>
              </div>
              <div class="titulo">
                <h5 class="nome">William H. M. Garey</h5>
                <h6 class="area">
                  Advogado | Nelson Garey Advogados Associados
                </h6>
              </div>
            </div>
          </b-carousel-slide>
          <b-carousel-slide class="slide">
            <div class="cont">
              <h5 class="titulo">Depoimentos</h5>
              <img src="../assets/depoimento-2.png" alt="" />
              <div class="descricao">
                <p>
                  “Seu corte tanto de camisas, bem como de ternos são
                  impecáveis,
                </p>
                <p>
                  muitos dos meus amigos tem elogiado a vestimenta. Recomendo
                </p>
                <p>
                  quem gosta de perfeição. Estamos nos servindo do trabalho do
                </p>
                <p>Trajar há mais de vinte anos.”</p>
              </div>

              <div class="titulo">
                <h5 class="nome">Domingos Orestes Chiomento</h5>
                <h6 class="area">DOC Contabilidade Empresarial</h6>
              </div>
            </div>
          </b-carousel-slide>
          <b-carousel-slide class="slide">
            <div class="cont">
              <h5 class="titulo">Depoimentos</h5>
              <img src="../assets/depoimento-3.png" alt="" />
              <div class="descricao">
                <p>
                  “Tenho a honra de afirmar que enquanto nossas vidas perdurarem
                  o meu conceito
                </p>
                <p>
                  é sempre melhor em relação ao Renee Trajar, sua pessoa, ao
                  profissional
                </p>
                <p>
                  competente e idôneo, sempre pontual, atencioso e preocupado em
                  atender da
                </p>
                <p>
                  melhor maneira os anseios de seus clientes, incluindo este
                  signatário.”
                </p>
              </div>
              <div class="titulo">
                <h5 class="nome">José Mauro Marques</h5>
                <h6 class="area">Advogado</h6>
              </div>
            </div>
          </b-carousel-slide>
          <b-carousel-slide class="slide">
            <div class="cont">
              <h5 class="titulo">Depoimentos</h5>
              <img src="../assets/depoimento-4.png" alt="" />
              <div class="descricao">
                <p>
                  “Conheço o excelente e qualificado trabalho do Renee Trajar e
                  sua equipe há décadas. Para
                </p>
                <p>
                  camisas e ternos, o Renee é imbatível, sempre com preços
                  justos, produtos de excelente
                </p>
                <p>
                  qualidade e especialmente tudo é feito com muito cuidado e
                  qualidade. Cumpre os prazos
                </p>
                <p>
                  com atendimento de alto nível. O Renee trabalha com perfeição
                  nos detalhes.”
                </p>
              </div>
              <div class="titulo">
                <h5 class="nome">Custódio Pereira</h5>
                <h6 class="area">
                  Membro do CONSOCIAL - Conselho Superior de Responsabilidade
                  Social da FIESP-SP
                </h6>
              </div>
            </div>
          </b-carousel-slide>
        </b-carousel>
      </div>

      <div>
        <b-form-radio-group
          class="mb-3"
          value-field="item"
          text-field="name"
          disabled-field="notEnabled"
        ></b-form-radio-group>
      </div>
    </div>

    <!-- depoimento 2 mobile -->

    <div class="dois">
      <div class="home-page">
        <b-carousel
          class="carousel-fade-dois"
          id="mainCarousel"
          :interval="4000"
          indicators
          controls
        >
          <b-carousel-slide class="slide-dois">
            <div class="cont">
              <h5 class="titulo">Depoimentos</h5>
              <img src="../assets/depoimento-1.png" alt="" />
              <div class="descricao">
                <p class="paragrafo-dois">
                  “Sou cliente do Renee há uns 12 anos. Nosso primeiro contato
                  foi por intermédio de meu pai, que já tem uma história de
                  décadas com o querido Renee. O excelente atendimento antes e
                  pós venda e a alta qualidade dos materiais usados colocam a
                  Renee Trajar em um patamar acima dos demais do ramo.”
                </p>
              </div>
              <div class="titulo">
                <h5 class="nome">William H. M. Garey</h5>
                <h6 class="area">
                  Advogado | Nelson Garey Advogados Associados
                </h6>
              </div>
            </div>
          </b-carousel-slide>
          <b-carousel-slide class="slide-dois">
            <div class="cont">
              <div class="conteudo-pad">
                <h5 class="titulo">Depoimentos</h5>
                <img src="../assets/depoimento-2.png" alt="" />
                <div class="descricao">
                  <p class="paragrafo-dois">
                    “Seu corte tanto de camisas, bem como de ternos são
                    impecáveis, muitos dos meus amigos tem elogiado a
                    vestimenta. Recomendo quem gosta de perfeição. Estamos nos
                    servindo do trabalho do Trajar há mais de vinte anos.”
                  </p>
                </div>
              </div>
              <div class="titulo">
                <h5 class="nome">Domingos Orestes Chiomento</h5>
                <h6 class="area">DOC Contabilidade Empresarial</h6>
              </div>
            </div>
          </b-carousel-slide>
          <b-carousel-slide class="slide-dois">
            <div class="cont">
              <h5 class="titulo">Depoimentos</h5>
              <img src="../assets/depoimento-3.png" alt="" />
              <div class="descricao">
                <p class="paragrafo-dois">
                  “Tenho a honra de afirmar que enquanto nossas vidas perdurarem
                  o meu conceito é sempre melhor em relação ao Renee Trajar, sua
                  pessoa, ao profissional competente e idôneo, sempre pontual,
                  atencioso e preocupado em atender da melhor maneira os anseios
                  de seus clientes, incluindo este signatário.”
                </p>
              </div>
              <div class="titulo">
                <h5 class="nome">José Mauro Marques</h5>
                <h6 class="area">Advogado</h6>
              </div>
            </div>
          </b-carousel-slide>
          <b-carousel-slide class="slide-dois">
            <div class="cont-dois">
              <h5 class="titulo">Depoimentos</h5>
              <img src="../assets/depoimento-4.png" alt="" />
              <div class="descricao">
                <p class="paragrafo-dois">
                  “Conheço o excelente e qualificado trabalho do Renee Trajar e
                  sua equipe há décadas. Para camisas e ternos, o Renee é
                  imbatível, sempre com preços justos, produtos de excelente
                  qualidade e especialmente tudo é feito com muito cuidado e
                  qualidade. Cumpre os prazos com atendimento de alto nível. O
                  Renee trabalha com perfeição nos detalhes.”
                </p>
              </div>
              <div class="titulo">
                <h5 class="nome">Custódio Pereira</h5>
                <h6 class="area">
                  Membro do CONSOCIAL - Conselho Superior de Responsabilidade
                  Social da FIESP-SP
                </h6>
              </div>
            </div>
          </b-carousel-slide>
        </b-carousel>
      </div>

      <div>
        <b-form-radio-group
          class="mb-3"
          value-field="item"
          text-field="name"
          disabled-field="notEnabled"
        ></b-form-radio-group>
      </div>
    </div>
  </div>
</template>

<style>
.depoimentos,
.dois {
  padding-top: 100px;
  padding-bottom: 50px;
}

.slide {
  height: 500px;
}
.slide-dois {
  height: 630px;
}

.cont {
  padding-bottom: 50px;
}
.descricao {
  line-height: 18px;
}

.carousel-indicators li {
  margin: 20px 0 0 0;
  background-color: rgba(255, 255, 255, 0) !important;
  border-radius: 50% !important;
  width: 10px !important;
  height: 10px !important;
  border: 1.3px solid #014561 !important;
}
.carousel-indicators .active {
  background-color: #014561 !important;
}
.carousel-control-prev-icon {
  background: no-repeat center/cover url("../assets/prev.png") !important;
  height: 50px !important;
}
.carousel-control-next-icon {
  background: no-repeat center/cover url("../assets/next.png") !important;
  height: 50px !important;
}
.titulo {
  /* Títulos */

  font-family: "Cormorant";
  font-style: normal;
  font-weight: 300;
  font-size: 38px;

  /* identical to box height */

  align-items: center;
  text-align: center;

  /* Gray 6 */

  color: #f2f2f2;
}
.border-bot {
  border-bottom: 1px solid#70B0C4;
  width: 10px;

  text-align: center;
}
.img-depoimento {
  text-align: center;
  
}
.descricao {
  font-family: "Cormorant";
  font-style: italic;
  font-weight: 300;
  font-size: 17px;
  text-align: center;
  color: #c4c4c4;
}
.nome {
  font-family: "Cormorant";
  font-style: normal;
  font-weight: 400;
  font-size: 20px;
  text-align: center;

  color: #be9667;
}
.area {
  font-family: "Lato";
  font-style: normal;
  font-weight: 300;
  font-size: 14px;

  /* identical to box height */

  text-align: center;

  /* cinza */

  color: #949494;
}
.carousel-fade,
.carousel-fade-dois {
  background: no-repeat center/cover url("../assets/img-depoimento.png");
}
.conteudo-pad {
  padding-bottom: 30px;
}
.paragrafo-dois {
  line-height: 30px;
}
@media screen and (min-width: 320px) and (max-width: 767px) {
  .depoimentos {
    height: 600px;
  }
  .carousel-fade-dois {
    height: 620px;
  }

  .descricao {
    line-height: 14px;
  }
}
@media screen and (min-width: 500px) and (max-width: 600px) {
  .slide-dois {
    height: 590px;
  }
}

@media screen and (min-width: 768px) and (max-width: 905px) {
  .depoimentos {
    height: 500px;
  }
  .slide-dois {
    height: 500px;
  }
}

@media screen and (max-width: 905px) {
  .depoimentos {
    display: none;
  }
}
@media screen and (min-width: 906px) {
  .dois {
    display: none;
  }
}
</style>

