<template>
  <v-app class="painelImg">
    <v-row class="text-center">
      <v-col cols="12" sm="12">
        <br />
        <v-avatar size="200">
          <v-img
            :src="require('../assets/gabrielle.jpeg')"
            class="my-3"
            contain
            height="200"
          />
        </v-avatar>
      </v-col>

      <v-col class="mb-4" style="margin-top: -20px">
        <h1 class="titulo-h1" style="color: #f9a826">Gabrielle Maciel</h1>

        <h4 class="subtitulo-h4">
          Analista de Sistemas e Desenvolvedora de Software.
        </h4>
      </v-col>

      <v-col cols="12" sm="12" class="mb-4">
        <v-row justify="center">
          <v-btn
            class="ma-2"
            text
            icon
            color="orange lighten-2"
            href="mailto:gabriellemacieel@gmail.com"
          >
            <v-icon large> mdi-email</v-icon>
          </v-btn>
          <v-btn
            class="ma-2"
            text
            icon
            color="orange lighten-2"
            href="https://www.facebook.com/gabeesms"
          >
            <v-icon large> mdi-facebook</v-icon>
          </v-btn>
          <v-btn
            class="ma-2"
            text
            icon
            color="orange lighten-2"
            href="https://www.instagram.com/gabeesms/"
          >
            <v-icon large> mdi-instagram</v-icon>
          </v-btn>
          <v-btn
            class="ma-2"
            text
            icon
            color="orange lighten-2"
            href="https://twitter.com/gabeesms"
          >
            <v-icon large> mdi-twitter</v-icon>
          </v-btn>
          <v-btn
            class="ma-2"
            text
            icon
            color="orange lighten-2"
            href="https://www.linkedin.com/in/gabeesms/"
          >
            <v-icon large> mdi-linkedin</v-icon>
          </v-btn>
          <v-btn
            class="ma-2"
            text
            icon
            color="orange lighten-2"
            href="https://github.com/gabeesms"
          >
            <v-icon large> mdi-github</v-icon>
          </v-btn>
        </v-row>
      </v-col>

      <v-col cols="12" sm="12" class="mb-4">
        <v-row justify="center">
          <h4 class="subtitulo-h4" style="color: #f9a826">Sobre mim</h4>
        </v-row>

        <v-row justify="center" style="margin-top: 20px">
          <p class="sobremim-p">
            Bacharelado em Sistemas de Informação pela faculdade FAMETRO.
            <br />Estou cursando Especialização em Engenharia de Software na
            universidade PUC Minas.<br />Possuo experiência há mais de 3 anos
            com Desenvolvimento de Software Web.<br />Atualmente sou
            desenvolvedora FullStack na Kodigos Software.
            <br />
            <br />
            Foco em tecnologias: VueJs, Vuetify, C#, Entity Framework e SQL
            Server.
          </p>
        </v-row>
      </v-col>
    </v-row>

    <v-footer padless style="background-color: #f9a826; color: #ffff">
      <v-col class="text-center" cols="12">
        © {{ new Date().getFullYear() }} —
        <strong>Gabrielle Maciel da Silva</strong>
      </v-col>
    </v-footer>
  </v-app>
</template>

<script>
export default {
  name: "HelloWorld",

  data: () => ({}),
};
</script>

<style scoped>
.titulo-h1 {
  font-size: 4rem;
  font-family: "Roboto", "Helvetica", "Arial", sans-serif;
  font-weight: 300;
  line-height: 1.167;
  letter-spacing: -0.01562em;
}
.subtitulo-h4 {
  font-size: 1.5rem;
  font-family: "Roboto", "Helvetica", "Arial", sans-serif;
  font-weight: 400;
  line-height: 1.235;
  letter-spacing: 0.00735em;
}

.sobremim-p {
  font-size: 1.15rem;
  font-family: "Roboto", "Helvetica", "Arial", sans-serif;
  font-weight: 400;
  line-height: 1.235;
  letter-spacing: 0.00735em;
}
.painelImg {
  background-image: url("../assets/fundobranco.jpeg");
  background-size: cover;
  height: 100vh;
}
</style>
