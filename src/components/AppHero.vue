<script>
export default {
  data() {
    return {
      jumboName: "logo-vite.jpg",
    };
  },

  methods: {
    imagePath(imageName) {
      const imageUrl = new URL("../assets/img/" + imageName, import.meta.url);
      return imageUrl.href;
    },
  },
};
</script>

<template>
  <div class="container">
    <img :src="imagePath(jumboName)" alt="Jumbo" />
  </div>
</template>

<style></style>
