<template>
  <div>
    <v-carousel hide-delimiters>
      <v-carousel-item>
        <SimpleCard
          upTitle="USO EM ESCRITÓRIOS DE ADVOCACIA B2B"
          title="1. Aumento de eficiência"
          firstText="Os escritórios poderão gerenciar de forma mais eficiente o fluxo de trabalho de seus processos, desde a coleta de informações até a elaboração de pareceres e petições."
          IsReverse="true"
          src="imageEfficiency"
        />
      </v-carousel-item>
      <v-carousel-item>
        <SimpleCard
          upTitle="USO EM ESCRITÓRIOS DE ADVOCACIA B2B"
          title="2. Melhoria da qualidade do atendimento"
          firstText="Os escritórios terão acesso a informações completas e precisas sobre o caso, o que permite uma avaliação mais precisa e uma estratégia de defesa mais efetiva."
          IsReverse="true"
          src="imageEfficiency"
          showButton="true"
        />
      </v-carousel-item>
    </v-carousel>
  </div>
</template>

<script>
import SimpleCard from './simpleCard.vue';
export default {
  components: {
    SimpleCard,
  },
};
</script>

<style></style>
