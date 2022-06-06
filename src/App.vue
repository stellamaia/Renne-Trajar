
<template>
  <div class="app">
    <div class="banner">
      <NavBar />
      <HeaderComponent />
    </div>
    <MainComponent />
    <InformacoesMain />
    <QualidadeComponent />
    <PromocaoComponent />
    <ItensComponent />
    <DepoimentoComponent />
    <ContatoComponent />
    <FooterComponent />
  </div>
</template>

<script>
import NavBar from "./components/NavBar";
import HeaderComponent from "./components/HeaderComponent";
import MainComponent from "./components/MainComponent";
import InformacoesMain from "./components/InformacoesMain";
import QualidadeComponent from "./components/QualidadeComponent";
import PromocaoComponent from "./components/PromocaoComponent";
import ItensComponent from "./components/ItensComponent";
import DepoimentoComponent from "./components/DepoimentoComponent";
import ContatoComponent from "./components/ContatoComponent";
import FooterComponent from "./components/ FooterComponent";
export default {
  name: "App",
  components: {
    NavBar,
    HeaderComponent,
    MainComponent,
    InformacoesMain,
    QualidadeComponent,
    PromocaoComponent,
    ItensComponent,
    DepoimentoComponent,
    ContatoComponent,
    FooterComponent,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}
.banner {
  /* Banner_3 1 */

  width: 100%;
  height: calc(100vh - 150px);
  background: no-repeat center/cover url("./assets/Banner_3.png");
}

@media screen and (min-width: 320px) and (max-width: 768px) {
  .banner {
    height: 80vh;
    background-position: -800px;
    width: 100%;
  }
}
</style>