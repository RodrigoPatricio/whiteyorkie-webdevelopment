<template>
  <section>
    <div class="container">
      <div class="logo">
        <img src="@/assets/footer/logo.png" alt="Logo" />
        <h5>
          WHITEYORKIE DESENVOLVIMENTO E ANÁLISE DE SOFTWARE © 2022. Todos os
          direitos reservados.
        </h5>
      </div>
      <div class="flex">
        <div class="flex-box">
          <h3>ENDEREÇO</h3>
          <p>254 Avenida Ana Costa - Sala 41<br />Santos, SP - 11060-000</p>
          <p>hello@whiteyorkie.dev</p>
        </div>
        <div>
          <h3>Horário</h3>
          <p>De Segunda à Sexta<br>Das 09h às 17h</p>
          <h4>POLÍTICA DE PRIVACIDADE</h4>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style scoped>
section {
  background: #9e2b20;
  padding: 40px 0 0 0;
}
.container {
  display: flex;
  align-items: flex-start;
  justify-content: space-between;

  width: 95%;
  margin: 0 auto 0 auto;
}
.flex-box {
    width: 250px;
}
.flex {
    width: 500px;
    display: flex;
    align-items: center;
    justify-content: space-between;
}
.logo {
    
}
h3 {
  font-family: "Montserrat";
  font-style: normal;
  font-weight: 800;
  font-size: 16px;
  line-height: 150%;
  /* or 24px */

  display: flex;
  align-items: center;
  letter-spacing: 0.025em;

  color: #ffffff;
}
p {
  font-family: "Montserrat";
  font-style: normal;
  font-weight: 300;
  font-size: 14px;
  line-height: 150%;
  /* or 21px */

  display: flex;
  align-items: center;
  letter-spacing: 0.025em;

  color: #ffffff;
}
h5 {
  font-family: "Montserrat";
  font-style: normal;
  font-weight: 300;
  font-size: 10px;
  line-height: 150%;
  /* identical to box height, or 15px */

  color: #ffffff;
}
h4 {
  font-family: "Montserrat";
  font-style: normal;
  font-weight: 800;
  font-size: 14px;
  line-height: 150%;
  /* or 21px */

  display: flex;
  align-items: center;
  letter-spacing: 0.025em;
  text-decoration-line: underline;

  color: #ffffff;
}

</style>
