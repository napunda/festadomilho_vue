<template>
  <div class="home">
    <div class="home-content">
      <v-container class="container">
        <div class="d-flex justify-space-between">
          <div class="d-flex justify-center align-center flex-column item">
            <div>BAIXAR O REGIMENTO</div>
            <img height="60px" src="/img/regimento.png" alt="" />
          </div>
          <div class="d-flex justify-center align-center flex-column item">
            <div>BAIXAR O LOGOTIPO</div>
            <img height="80px" src="/img/logo.png" alt="" />
          </div>
        </div>
      </v-container>
    </div>
    <Footer />
  </div>
</template>

<script>
import Footer from "../components/Footer.vue";
export default {
  components: {
    Footer,
  },
};
</script>

<style>
.home {
  height: 100vh;
  background-image: url(/img/bg.jpg);
  background-size: cover;
  background-position: center;
}
.home-content {
  height: 92vh;
  background: url(/img/circle.png);
  background-position: top;
  background-repeat: no-repeat;
  padding-top: 200px;
}

.container {
  width: 52% !important;
}
.item {
  width: 50px;
  text-align: center;
}
</style>
