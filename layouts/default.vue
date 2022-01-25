<template>
  <div>
    <Navbar />
    <Slider />
    <div class="container">
      <Nuxt />
    </div>
    <Footer />
  </div>
</template>


<script>
import Navbar from "~/components/Navbar";
import Footer from "../components/Footer";
import Slider from "../components/Slider";

export default {
  components: {
    Slider,
    Footer,
    Navbar,
  }
};
</script>

<style>

</style>
