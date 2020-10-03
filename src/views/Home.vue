<template>
  <div class="container-column">
    <div id="info-link">
      <router-link to="/about"
        ><img
          src="https://api-lunacy.icons8.com/api/assets/7ff850a3-2f5a-4504-805b-db15e02b711d/icons8_info.png"
          alt="Info Icon"
      /></router-link>
    </div>
    <h1 id="easydex-title">easydex</h1>
    <p id="cathphrase">Gotta index em' all!</p>
    <img
      src="https://api-lunacy.icons8.com/api/assets/84996d02-1669-4707-90d4-9ff57b1d87fc/PokedexIcon.png"
    />

    <div class="container-column">
      <p class="main-font" id="browse-text">Browse</p>
      <router-link to="/PokemonDisplay">
        <img
          id="browse-button"
          src="https://api-lunacy.icons8.com/api/assets/9fde4770-adb5-4549-b64c-565ef0c3e487/Triangle.png"
          alt="Browse Button"
        />
      </router-link>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Home'
}
</script>

<style scoped>
#easydex-title {
  color: #f8c822;
  font-family: 'Bangers', cursive;
  font-weight: 400;
  font-size: 72px;
  -webkit-text-stroke: 3px #1a56c1;
  margin-bottom: 0px;
}
#cathphrase {
  color: #808080;
  font-family: 'Varela Round', sans-serif;
  font-size: 16px;
  font-weight: 400;
  margin-top: 0px;
  margin-bottom: 35px;
}
#browse-text {
  margin-top: 85px;
  margin-bottom: 12px;
}
#browse-button {
  display: block;
  margin-bottom: 40px;
}
#info-link {
  align-self: flex-end;
  margin-top: 15px;
  margin-right: 15px;
}
</style>
