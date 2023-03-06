<template>
  <div>
    <v-carousel hide-delimiters show-arrows="hover">
      <v-carousel-item>
        <SimpleCard
          upTitle="USO EM ESCRITÓRIOS DE ADVOCACIA B2B"
          title="1. Maior comodidade"
          firstText="A possibilidade de preencher os dados do processo de forma on-line e intuitiva, permite aos clientes uma experiência mais conveniente e confortável."
          src="imageConvenience"
        />
      </v-carousel-item>
      <v-carousel-item>
        <SimpleCard
          upTitle="USO EM ESCRITÓRIOS DE ADVOCACIA B2B"
          title="2. Redução de custos"
          firstText="A antecipação dos dados necessários para abertura do processo, permite uma redução no tempo de trabalho do advogado envolvido no processo, e com isso, há a redução dos custos no atendimento."
          src="imageConvenience"
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
