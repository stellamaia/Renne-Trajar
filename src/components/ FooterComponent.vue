<template>
  <div class="footer">
    <b-container>
      <b-row>
        <b-col lg="12">
          <img
            class="conteudo-img"
            alt="sacola"
            src="../assets/logo-black-footer.png"
          />

          <b-row>
            <b-col cols="8" sm="6" lg="5" xl="5" class="cnpj"
              >CNPJ:04.487.685/0001-01</b-col
            >
            <b-col cols="4" sm="6" lg="7" xl="7" class="copy"
              >Copyright: 2021 © Renee Trajar - Todos os direitos
              reservados.</b-col
            >
          </b-row>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>
<style scoped>
.footer {
  border: 1px solid #be9667;
  padding: 20px 20px 30px 70px;
}
.conteudo-img {
  height: 60px;
}
.cnpj {
  font-family: "Poppins";
  font-style: normal;
  font-weight: 300;
  font-size: 14px;
  line-height: 21px;
  padding-top: 15px;
  /* Gray 4 */

  color: #bdbdbd;
}
.copy {
  font-family: "Poppins";
  font-style: normal;
  font-weight: 300;
  font-size: 18px;
  line-height: 21px;
  text-align: center;
  text-align: end;
  /* Gray 2 */
  color: #4f4f4f;
}
</style>