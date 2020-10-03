<template>
  <router-view />
</template>

<style>
body {
  background-color: #343434;
  margin: 0;
  padding: 0;
}

.main-font {
  width: 144px;
  height: 24px;
  color: #616161;
  font-family: 'Press Start 2P', cursive;
  font-size: 24px;
  font-weight: 400;
  line-height: 24px;
}
.container-column {
  display: flex;
  flex-direction: column;
  align-items: center;
}
.container-row {
  display: flex;
  flex-direction: row;
}
#app {
  margin: auto;
  width: 100%;
  height: 100vh;
  background-color: white;
}
</style>
