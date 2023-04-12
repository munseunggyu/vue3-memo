<template>
  <Header />
  <Memo />
  <Ground />
  <Footer />
</template>

<script>
import Footer from "./components/Footer.vue";
import Ground from "./components/Ground.vue";
import Header from "./components/Header.vue";
import Memo from "./components/Memo.vue";
export default {
  name: "App",
  components: {
    Ground,
    Header,
    Footer,
    Memo,
  },
};
</script>

<style></style>
