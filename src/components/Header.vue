<template>
  <header>
    <a href="/">
      <img src="../assets/dc-logo.png" alt="" />
    </a>
    <ul>
      <li>CHARACTERS</li>
      <li>COMICS</li>
      <li>MOVIES</li>
      <li>TV</li>
      <li>GAMES</li>
      <li>COLLECTIBLES</li>
      <li>VIDEOS</li>
      <li>FANS</li>
      <li>NEWS</li>
      <li>SHOP</li>
    </ul>
  </header>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style scoped>
header {
  display: inline-flex;
  margin-top: 30px;
  margin-left: 200px;
  font-family: sans-serif;
}
a {
  margin-right: 100px;
  height: 30px;
}

li {
  list-style: none;
  display: inline-block;
  margin: 10px;
}
.container {
  width: 100%;
  background-image: url(../assets/jumbotron.jpg);
}
</style>