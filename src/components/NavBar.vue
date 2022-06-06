<template>
  <div class="NavBar">
    <div :class="isNav1 ? 'navbar-1' : 'navbar-2'" class="Navbar 1">
      <b-container class="conteudo-mobile">
        <b-row class="text-center">
          <b-col cols="12" sm="12" md="1">
            <img
              class="conteudo-mobile__img"
              alt="sacola"
              :src="
                isNav1
                  ? require('../assets/logo-black.png')
                  : require('../assets/logo-white.png')
              "
            />
          </b-col>

          <b-col cols="12" sm="1" md="">
            <div class="conteudo-desktop__lista">
              <b-link class="header__link" href="#empresa">Empresa</b-link>
              <b-link class="header__link" href="#camisaria">Camisaria</b-link>
              <b-link class="header__link" href="#alfaiataria"
                >Alfaiataria</b-link
              >
              <b-link class="header__link" href="#depoimentos"
                >Depoimentos</b-link
              >
              <b-link class="header__link" href="#contato">Contato</b-link>
            </div>
          </b-col>
        </b-row>
      </b-container>

      <div class="conteudo-desktop">
        <b-row class="text-center">
          <b-col lg="2" xl="2">
            <img
              class="conteudo-mobile__img"
              alt="sacola"
              :src="
                isNav1
                  ? require('../assets/logo-black.png')
                  : require('../assets/logo-white.png')
              "
            />
          </b-col>
          <b-col lg="4" xl="3">
            <!-- -->
          </b-col>
          <b-col lg="4" xl="7">
            <div class="conteudo-desktop__lista">
              <b-link class="header__link" href="#empresa">Empresa</b-link>
              <b-link class="header__link" href="#camisaria">Camisaria</b-link>
              <b-link class="header__link" href="#alfaiataria"
                >Alfaiataria</b-link
              >
              <b-link class="header__link" href="#depoimentos"
                >Depoimentos</b-link
              >
              <b-link class="header__link" href="#contato">Contato</b-link>
            </div>
          </b-col>
        </b-row>
      </div>
    </div>
  </div>
</template>
<style scoped>
.NavBar {
  height: 100px;
}
.conteudo-mobile__img {
  height: 60px;
}
.header__link {
  text-decoration: none;
  text-transform: uppercase;
  padding-right: 10px;
  font-weight: 300;
  font-size: 12px;
  color: #949494;
}
.header__link:hover {
  color: rgba(2, 75, 104, 0.68);
}
.active {
  text-decoration: none;
  color: #91664c;
}
@media screen and (min-width: 320px) and (max-width: 1024px) {
  .header__link {

    font-size: 17px;
  }
  .conteudo-desktop {
    display: none;
  }
}
@media screen and (min-width: 320px) and (max-width: 767px) {
  .header__link {

    color: #949494;
    font-weight: 400;
  }
      .conteudo-desktop__lista{
          padding-top: 20px;
      }
  
}
@media screen and (min-width: 768px) and (max-width: 1024px) {
  .header__link {
    color: #949494;
    font-size: 16px;
  }
    .conteudo-desktop__lista{
          padding: 20px 0px 0 20px ;
      }
  
}
@media screen and (min-width: 1025px) and (max-width: 1200px) {
  .conteudo-mobile {
    display: none;
  }
  .header__link {
    color: #949494;
    font-size: 16px;
  }
}
@media screen and (min-width: 1201px) {
  .conteudo-mobile {
    display: none;
  }
  .header__link {
    color: #949494;
    font-size: 20px;
  }
}
.navbar-2 {
  top: 0;
  left: 0;

  transition: 0.5s all;

  padding: 20px 0 20px 0;
  height: 120px;
  width: 100%;

  position: fixed;

  background: linear-gradient(180deg, #000000 29.73%, rgba(0, 0, 0, 0) 100%);
}
.navbar-1 {
  position: fixed;
  padding-top: 20px;
  top: 0;
  left: 0;
  z-index: 3;
  height: 140px;
  width: 100%;
  transition: 0.5s all;

  background: #ffffff !important;
}
</style>
<script>
export default {
  name: "NavBar",
  data() {
    return {
      isNav1: true,
      stickyClass: "is_sticky",
      scrollPosition: 0,
    };
  },
  props: {
    msg: String,
  },
  created() {
    window.addEventListener("scroll", this.handleScroll);
  },
  // destroyed () {
  //         window.removeEventListener('scroll', this.handleScroll);
  // },
  unmounted() {
    window.removeEventListener("scroll", this.handleScroll);
  },
  methods: {
    handleScroll() {
      this.scrollPosition = window.scrollY;
      if (this.scrollPosition >= 100) {
        this.isNav1 = true;
      } else {
        this.isNav1 = false;
      }
    },
  },
};
</script>
