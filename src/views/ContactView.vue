<template>
  <Header />
  <section class="contact">
    <div class="mini-showcase"></div>
    <div class="form">
      <h1>Vamos<br />conversar?</h1>
      <div id="hubspotForm" v-once></div>
      <p>DESIGN•ENGINEERING•DEPLOYMENT</p>
    </div>
  </section>
  <Footer />
</template>

<script>
import Header from "@/components/Header.vue";
import Footer from "@/components/Footer.vue";

export default {
  name: "ContactView",
  components: {
    Header,
    Footer,
  },
  mounted() {
    const script = document.createElement("script");
    script.src = "https://js.hsforms.net/forms/shell.js";
    document.body.appendChild(script);
    script.addEventListener("load", () => {
      if (window.hbspt) {
        window.hbspt.forms.create({
          portalId: "21285312",
          formId: "61fce5f8-83e7-46ed-8a05-1554e2e2a542",
          target: "#hubspotForm",
        });
      }
    });
  },
};
</script>

<style scoped>
.contact {
  background: black;
}
.mini-showcase {
  width: 100%;
  height: 300px;

  background: url("@/assets/contact-page/mini-showcase.png");
  box-shadow: 0px 5px 50px 5px rgba(0, 0, 0, 0.25);
}
.form {
  height: 1100px;
  background: url("@/assets/contact-page/background-pattern.png") no-repeat;
}
.form h1 {
  padding: 50px 0 0 0;
  margin: 0 0 0 150px;

  font-family: "Montserrat";
  font-style: normal;
  font-weight: 800;
  font-size: 64px;
  line-height: 78px;

  color: #ffffff;
}
.contact p {
  font-family: "Montserrat";
  font-style: normal;
  font-weight: 800;
  font-size: 24px;
  line-height: 0%;
  /* identical to box height, or 0px */

  text-align: center;
  letter-spacing: 1em;

  color: #ffffff;
}
#hubspotForm {
  width: 525px;
  margin: 50px 0 0 150px;
}
</style>
