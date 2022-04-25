<template>
  <div class="home">
    <center>
      <img
        alt="progra" width="500" 
        src="https://www.silicon.es/wp-content/uploads/2015/03/Fuente-Shutterstock_Autor-McIek_codigo-programacion.jpg"
      />
    </center>
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "Home",
  components: {
    HelloWorld,
  },
};
</script>
