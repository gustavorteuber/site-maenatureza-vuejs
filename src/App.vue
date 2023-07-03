<template>
  <navbar />
  <carousel />
  <cards />
  <footerinfo />
</template>
<script>
import navbar from "./components/Navbar.vue";
import carousel from "./components/Carousel.vue";
import cards from "./components/CardsJail.vue";
import footerinfo from "./components/Footer.vue";

export default {
  components: { navbar, carousel, cards, footerinfo },
};
</script>
