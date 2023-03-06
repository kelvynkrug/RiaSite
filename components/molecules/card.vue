<template>
  <div class="container d-flex">
    <v-col cols="8">
      <v-row>
        <h5 class="upTitleCard">{{ upTitle }}</h5>
      </v-row>
      <v-row>
        <h3 class="titleCard">{{ title }}</h3>
      </v-row>
      <v-row>
        <p class="textCard">
          {{ firstText }}
        </p>
        <p>
          {{ secondText }}
        </p>
      </v-row>
      <v-row>
        <Button
          text="Experimente Grátis"
          color="#084461"
          width="287px"
          height="60px"
          class="mt-6"
          isRounded="true"
          isWhite="true"
        ></Button>
      </v-row>
    </v-col>
    <v-col>
      <img class="imageAbout" :src="require(`@/assets/images/${src}.png`)" />
    </v-col>
  </div>
</template>

<script>
import Button from '../atoms/button.vue';
export default {
  components: {
    Button,
  },
  props: {
    title: {
      type: String,
      default: null,
    },
    upTitle: {
      type: String,
      default: null,
    },
    firstText: {
      type: String,
      default: '',
    },
    secondText: {
      type: String,
      default: '',
    },
    src: {
      type: String,
      default: null,
    },
  },
};
</script>

<style>
.card {
  width: 100%;
  border-radius: 32px;
  margin-top: 100px;
}

.titleCard {
  margin-top: 2px;
  width: 495px;
  font-size: 40px;
  text-align: justify;
}

.upTitleCard {
  margin-top: 25px;
}

.textCard {
  margin-top: 30px;
  width: 495px;
  font-size: 20px;
  text-align: justify;
}

.imageAbout {
  width: 100%;
  height: 100%;
  border-radius: 16px;
}
</style>
