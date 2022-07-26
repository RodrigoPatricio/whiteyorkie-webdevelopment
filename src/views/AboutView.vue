<template>
  <Header />
  <section class="about">
    <div class="mini-showcase"></div>
    <div class="about-us">
      <h1>Sobre Nós</h1>
      <div class="flexbox">
        <div class="box">
          <h2>Quem somos?</h2>
          <p>
            Somos conhecidos por desafiar a forma como as histórias digitais são
            contadas. Nosso trabalho geralmente incorpora tudo, desde o design
            da página de destino até o desenvolvimento de software personalizado
            e a criação complexa de e-commerce. Se for possível, whiteyorkie
            pode fazê-lo.
          </p>
        </div>
        <div class="box">
          <h2>Nossa atuação</h2>
          <p>
            Somos especialistas em design, engenharia e implementação de
            soluções tecnológicas. Auxiliamos organizações que tem como objetivo
            aprimorar o desempenho interno, obter maior presença digital e
            expandir seu alcance através do uso de plataformas exclusivas
            desenvolvidas sob medida para seus negócios.
          </p>
        </div>
      </div>
    </div>
  </section>
  <Footer />
</template>

<script>
import Header from "@/components/Header.vue";
import Footer from "@/components/Footer.vue";

export default {
  name: "AboutView",
  components: {
    Header,
    Footer,
  },
};
</script>

<style scoped>
.mini-showcase {
  width: 100%;
  height: 300px;

  background: url("@/assets/contact-page/mini-showcase.png");
  box-shadow: 0px 5px 50px 5px rgba(0, 0, 0, 0.25);
}
.about-us h1 {
  margin-top: 65px;

  text-align: center;
  font-family: "Montserrat";
  font-style: normal;
  font-weight: 700;
  font-size: 64px;
  line-height: 78px;
  /* identical to box height */

  color: #000000;
}
.about-us h2 {
  font-family: "Montserrat";
  font-style: normal;
  font-weight: 600;
  font-size: 36px;
  line-height: 44px;
  /* identical to box height */

  color: #000000;
}
.about-us p {
  font-family: "Lato";
  font-style: normal;
  font-weight: 500;
  font-size: 24px;
  line-height: 150%;

  color: #000000;
}
.flexbox {
  margin: 120px 0 150px 0;

  display: flex;
  align-items: top;
  justify-content: space-evenly;
}
.box {
  width: 600px;
}
</style>
