<template>
  <div id="app">
    <img alt="image" src="./assets/img/dodninja.png">
    <div id="nav">
      <router-link to="/">Home |</router-link>
      <router-link to="/about"> About |</router-link>
      <router-link to="/work"> Works</router-link>
      <router-link to="/soroban"></router-link>
    </div>
    <router-view/>
  </div>
</template>

<style>
#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}

#washi{
  width: 20%;
  height: 20%;
  margin-left: 100px;   /* 外側の余白を40pxにする */
}

#nav {
  padding: 30px;

}



#nav a {
  font-weight: bold;
  color: #FD974F;
}

#nav a.router-link-exact-active {
  color: skyblue;
}
</style>
