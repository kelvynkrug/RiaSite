<template>
  <div class="card">
    <div class="container">
      <v-row>
        <v-col>
          <h2 class="titleInformation">
            Colete informações automaticamente <br />
            sobre um novo caso
          </h2>
          <p class="textInformation">
            Com o Briefing Jurídico, o advogado pode obter dados relevantes
            sobre o caso, <br />
            como informações das partes envolvidas, ocorrências, documentos
            relacionados, <br />
            precedentes, entre outros detalhes importantes antes da primeira
            reunião.
          </p>
        </v-col>
      </v-row>
      <v-row class="mt-16">
        <v-col cols="2">
          <v-icon class="icon">mdi-account-tie</v-icon>
          <p>Briefing</p>
        </v-col>
        <v-col cols="2">
          <v-icon class="icon">mdi-message-question-outline</v-icon>
          <p>Perguntas e respostas</p>
        </v-col>
        <v-col cols="2">
          <v-icon class="icon">mdi-comment-text-outline</v-icon>
          <p>Resumo do caso</p>
        </v-col>
        <v-col cols="2">
          <v-icon class="icon">mdi-head-dots-horizontal-outline</v-icon>
          <p>Insights</p>
        </v-col>
        <v-col cols="2">
          <v-icon class="icon">mdi-file-document-outline</v-icon>
          <p>Pré Parecer</p>
        </v-col>
        <v-col cols="2">
          <v-icon class="icon">mdi-gesture-tap</v-icon>
          <p>Autoatendimento</p>
        </v-col>
      </v-row>
    </div>
  </div>
</template>

<script></script>

<style>
.card {
  width: 100%;
  height: 648px;
  opacity: 0, 5;
  background-color: #f2f1ed;
  text-align: center;
}

.titleInformation {
  font-size: 40px;
  margin-top: 128px;
}

.textInformation {
  font-size: 20px;
  margin-top: 24px;
}

.icon {
  font-size: 48px !important;
}
</style>
