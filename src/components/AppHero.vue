<script>
export default {
  data() {
    return {
      kobe: {
        img: "src/components/img/kobe.jpg",
        title: "Kobe Bryant",
        text: "One of the greatest to ever play the game",
      },
    };
  },
};
</script>

<template>
  <div class="hero-container">
    <img :src="kobe.img" :alt="kobe.title" />
    <div class="hero-text">
      <h2>{{ kobe.title }}</h2>
      <p>{{ kobe.text }}</p>
    </div>
  </div>
</template>

<style scoped>
.hero-container {
  max-width: 1200px;
  position: relative;
  margin: auto;
}
img {
  width: 100%;
}
.hero-text {
  width: 100%;
  font-size: 2rem;
  padding: 0.5rem;
  color: purple;
  text-align: center;
  position: absolute;
  bottom: 0;
  left: 50%;
  transform: translate(-50%);
  background-color: rgba(245, 245, 220, 0.5);
}
</style>
