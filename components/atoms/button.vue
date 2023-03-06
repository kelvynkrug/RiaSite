<template>
  <div>
    <v-btn
      :width="width"
      :height="height"
      :color="color"
      :elevation="elevation"
      class="btn"
      :class="{ rounded: isRounded, textWhite: isWhite }"
    >
      {{ text }}
    </v-btn>
  </div>
</template>

<script>
export default {
  props: {
    text: {
      type: String,
      default: null,
    },
    width: {
      type: String,
      default: null,
    },
    height: {
      type: String,
      default: null,
    },
    elevation: {
      type: Number,
      default: 0,
    },
    color: {
      type: String,
      default: null,
    },
    isRounded: {
      type: Boolean,
      default: false,
    },
    isWhite: {
      type: Boolean,
      default: false,
    },
  },
};
</script>

<style scoped>
.btn {
  text-transform: capitalize;
  padding: 18px, 20px, 18px, 20px;
}

.rounded {
  border-radius: 16px !important;
}

.textWhite {
  color: #fff;
}
</style>
