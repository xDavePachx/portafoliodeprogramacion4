<template>
  <div id="app">
    <div id="nav">
      <img
        alt="pokemon logo"
        width="50"
        src="https://pngimg.com/uploads/pokeball/pokeball_PNG19.png"
      />|
      <router-link to="/">Home</router-link> |
      <router-link to="/about">Desarrollo</router-link>|
      <router-link to="/evidencias">Evidencias</router-link>|
      <router-link to="/fechas">Fechas</router-link>
    </div>
    <router-view />
  </div>
</template>

<style>
.app {
  color: #5daddb;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: justify;
  color: #213c5f;
}

#nav {
  padding: 15px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
