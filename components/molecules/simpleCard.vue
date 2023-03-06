<template>
  <div class="container">
    <v-card class="card d-flex" elevation="0" :class="{ reverse: IsReverse }">
      <v-col cols="12" md="6">
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
        </v-row>
        <v-row>
          <Button
            v-if="showButton"
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
      <v-col class="colunaImg ml-2" cols="12" md="6">
        <img class="image" :src="require(`@/assets/images/${src}.png`)" />
      </v-col>
    </v-card>
  </div>
</template>

<script>
export default {
  props: {
    showButton: {
      type: Boolean,
      default: false,
    },
    IsReverse: {
      type: Boolean,
      default: false,
    },
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

<style scoped>
.titleCard {
  margin-top: 2px;
  width: 495px;
  font-size: 40px;
  text-align: justify;
}

.textCard {
  width: 495px;
  font-size: 20px;
  text-align: justify;
}
.reverse {
  flex-direction: row-reverse !important ;
}

.upTitleCard {
  font-size: 14px;
}

.image {
  width: 370px;
  height: 370px;
  border-radius: 32px;
  margin: 0;
}
</style>
