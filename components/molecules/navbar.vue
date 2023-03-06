<template>
  <div>
    <v-app-bar elevation="0" class="appbar">
      <img src="../../assets/images/Logo.png" alt="Logo RIA" class="logo" />
      <Button class="left-buttons" text="Quem somos"></Button>
      <Button class="left-buttons" text="Blog"> </Button>
      <v-spacer></v-spacer>
      <Button
        elevation="2"
        text="Experimente Grátis"
        color="#084461"
        rounded="true"
        isWhite="true"
      ></Button>
    </v-app-bar>
  </div>
</template>

<script>
import Button from '../atoms/button.vue';
export default {
  components: {
    Button,
  },
};
</script>

<style scoped>
.left-buttons {
  margin-left: 48px;
}

.logo {
  margin-left: 71px;
}

.appbar {
  height: 48px;
}
</style>
