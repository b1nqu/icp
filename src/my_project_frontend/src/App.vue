<template>
  <div class="app-container">
    <Header />
    <aboutYou />
    <Skills />
    <Projects />
    <Contant />
  </div>
</template>
<script>
  import Header from "./components/Header.vue";
  import aboutYou from "./components/aboutYou.vue";
  import Contant from "./components/Contant.vue";
  import Projects from "./components/Projects.vue";
  import Skills from "./components/Skills.vue";

  export default {
    name: 'App',
    components: {
      Header,
      aboutYou,
      Contant,
      Projects,
      Skills,
    },
  };
</script>