<template>
  <div class="container-column">
    <router-link to="/">
      <div class="container-column navigate-button" id="home">
        <img
          class="img-home"
          src="https://api-lunacy.icons8.com/api/assets/3fdf1ef5-e68c-4fa6-ba52-881ae4e94d35/Triangle.png"
          alt="Navigation arrow"
        />
        <p class="text-margin">Home</p>
      </div>
    </router-link>
    <div class="container-row">
      <div class="navigate-button container-column" id="search">
        <p class="text-margin">Search</p>
        <img
          class="img-search-filter"
          src="https://api-lunacy.icons8.com/api/assets/3fdf1ef5-e68c-4fa6-ba52-881ae4e94d35/Triangle.png"
          alt="Navigation arrow"
        />
      </div>
      <div class="container-column navigate-button" id="filter">
        <p class="text-margin">Filter</p>
        <img
          class="img-search-filter"
          src="https://api-lunacy.icons8.com/api/assets/3fdf1ef5-e68c-4fa6-ba52-881ae4e94d35/Triangle.png"
          alt="Navigation arrow"
        />
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
a {
  text-decoration: none;
}
.navigate-button {
  color: #616161;
  font-family: 'Press Start 2P', cursive;
  font-size: 24px;
  padding-left: 10px;
  padding-right: 10px;
}
.text-margin {
  margin: 15px 0px;
  text-decoration: none;
}
.img-search-filter {
  margin-bottom: 5px;
}
.img-home {
  margin-top: 5px;
  transform: rotateX(180deg);
}
#home {
  padding-left: 116px;
  padding-right: 117px;
  border-bottom: solid 1px #616161;
  border-left: solid 1px #616161;
  border-right: solid 1px #616161;
}
#filter {
  border-bottom: solid 1px #616161;
  border-right: solid 1px #616161;
}
#search {
  border-bottom: solid 1px #616161;
  border-right: solid 1px #616161;
  border-left: solid 1px #616161;
}
</style>
