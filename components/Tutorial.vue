<template>
  <v-app>
    <Navbar />
    <alert />
    <Card
      upTitle="RIA: Inteligência Jurídica"
      title="A tecnologia que garante estratégia comercial"
      firstText="Briefing Jurídico oferece conforto e segurança para seus clientes se comunicarem e agilidade, conhecimento e valor para você antes da sua primeira reunião. Com informações antecipadas sobre o caso, você pode antecipar estratégias e aplicar retóricas específicas para o fechamento do contrato na primeira reunião oficial."
      src="imageTopHome"
    />
    <h2 style="font-size: 40px; text-align: center; margin-top: 148px">
      Com o RIA, você tem insights valiosos
    </h2>
    <p style="font-size: 20px; text-align: center; margin-bottom: 150px">
      que te ajudam a tomar decisões estratégicas para o sucesso da sua primeira
      <br />
      reunião, e assim, fechar seu novo contrato.
    </p>
    <div>
      <CarouselEfficiency />
      <CarouselConvenience />
    </div>

    <CardInformation />
  </v-app>
</template>

<script>
import Navbar from '../components/molecules/navbar.vue';
import Card from '../components/molecules/card.vue';
import alert from '../components/atoms/alert.vue';
import SimpleCard from './molecules/simpleCard.vue';
import CardInformation from '../components/molecules/cardCollectInformation.vue';
import CarouselEfficiency from './molecules/carouselEfficiency.vue';
import CarouselConvenience from './molecules/carouselConvenience.vue';
export default {
  components: {
    Navbar,
    alert,
    Card,
    SimpleCard,
    CardInformation,
    CarouselEfficiency,
    CarouselConvenience,
  },
};
</script>

<style></style>
