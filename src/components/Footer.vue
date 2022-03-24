<template>
  <div class="footer d-flex">
    <div class="logo-grupo d-flex align-center justify-end pr-16">
      <div class="logo">
        <img src="/img/grupofasipe.png" alt="" />
      </div>
    </div>
    <div class="copy white--text d-flex justify-center align-center pl-16">
      &copy; Copyright &#8231; Todos os direitos reservados &#8231; GRUPO FASIPE
      EDUCACIONAL
    </div>
  </div>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style scoped>
.footer {
  width: 100%;
  height: 8vh;
  background-color: #244913;
  box-shadow: 0px -6px 10px 0px rgba(0, 0, 0, 0.49);
  opacity: 95%;
}

.logo-grupo {
  background-color: #fff;
  width: 30%;
  height: 100%;
}

.logo-grupo img {
  height: 60px;
  width: 100%;
  filter: grayscale(100%);
}
.copy {
  font-size: 14px;
}
</style>
