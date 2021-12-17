<template>
  <div id="app">
    <Title />
    <Banner />
  </div>
</template>

<script>
import Title from "./components/Title.vue";
import Banner from "./components/Banner.vue";

export default {
  name: "App",
  components: {
    Title,
    Banner,
  },
};
</script>

<style>
*{
  margin: 0px;
  padding: 0px;
  box-sizing: border-box;
}
</style>
