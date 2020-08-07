<template>
  <svg :width="getWidth" :height="getHeight" x="0.0" y="0.0" viewBox="0 0 121 78">
    <path fill="currentColor" fill-rule="nonzero" d="M90.5 3C90.5 1.34315 91.8431 0 93.5 0H117.5C119.157 0 120.5 1.34315 120.5 3V44.5C120.5 46.1569 119.157 47.5 117.5 47.5H93.5C91.8431 47.5 90.5 46.1569 90.5 44.5V3Z"/>
    <path fill="currentColor" fill-rule="nonzero" d="M54.878 22.7407C56.7676 20.8498 60 22.1881 60 24.8613V74.5385C60 76.1953 58.6569 77.5385 57 77.5385H3C1.34315 77.5385 0 76.1953 0 74.5385V24.7844C0 22.1112 3.23238 20.7729 5.122 22.6637L27.9164 45.4728C29.0882 46.6453 30.9887 46.6453 32.1604 45.4728L54.878 22.7407Z"/>
  </svg>
</template>

<script>
export default {
  props: {
    width: {
      type: Number,
      default: 40
    }
  },

  computed: {
    getWidth() {
      return this.width;
    },

    getHeight() {
      return Math.ceil((this.getWidth / 64) * 64);
    }
  }
};
</script>

