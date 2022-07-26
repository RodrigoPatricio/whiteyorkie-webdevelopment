<template>
  <div>
    <img :src="require(`@/assets/home-page/blog/${imageUrl}`)" alt="cover" />
    <h3>{{ cardTitle }}</h3>
    <p>{{ cardDate }}</p>
    <h4>{{ cardText }}</h4>
    <button>Leia este artigo</button>
  </div>
</template>

<script>
export default {
  name: "LargeCard",
  props: {
    cardTitle: String,
    cardDate: String,
    cardText: String,
    imageUrl: String,
  },
};
</script>

<style scoped>
div {
  background-color: #9e2b20;
  width: 450px;
  height: 660px;

  border-radius: 8px;
  box-shadow: 4px 12px 12px rgba(0, 0, 0, 0.25);
}
h3 {
  margin: 24px 0 0 20px;
  width: 90%;

  font-family: "Montserrat";
  font-style: normal;
  font-weight: 800;
  font-size: 20px;
  line-height: 24px;

  color: #ffffff;
}
p {
  margin: 10px 0 0 20px;

  font-family: "Georgia";
  font-style: normal;
  font-weight: 400;
  font-size: 16px;
  line-height: 18px;

  color: #ffffff;
}
h4 {
  margin: 22px 0 0 20px;
  width: 90%;

  font-family: "Lato";
  font-style: normal;
  font-weight: 400;
  font-size: 16px;
  line-height: 150%;
  /* or 24px */

  letter-spacing: 0.02em;

  color: #ffffff;
}
button {
  margin: 20px 0 0 20px;

  width: 176px;
  height: 36px;

  background: #000000;
  border-radius: 50px;

  font-family: "Montserrat";
  font-style: normal;
  font-weight: 800;
  font-size: 16px;
  line-height: 20px;
  /* identical to box height */

  color: #ffffff;

  cursor: pointer;
}
</style>
