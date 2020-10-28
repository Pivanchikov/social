<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}


body {
    margin: 0;
    font-size: 18px;
    background-color: rgb(240, 236, 236);
}

 h1,ul, li{
    margin: 0;
    list-style-type: none;
}

input, input:focus {
    color:darkgrey;
    border: none;
}


a {
    cursor: pointer;
    text-decoration: none;
    color: inherit;
}

.container {
    width: 1200px;
    margin: 0 auto;
}

.flex {
    display: flex;
    justify-content: space-between;
}
</style>
