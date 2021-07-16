<template>
  <div>
    <Navbar />
    <div class="container">
      <Hero />
      
      <Card />
    </div>
  </div>
</template>

<script>
import Navbar from "@/components/Navbar.vue";
import Hero from "@/components/Hero.vue";
import Card from "@/components/Card.vue";

export default {
  name: "Home",
  components: {
    Navbar,
    Hero,
    Card
  },
};
</script>
