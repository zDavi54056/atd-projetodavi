<template>
  <header>
    <span>Home</span>
    <span>|</span>
    <span>Jogadores</span>
    <span>|</span>
    <span>Times</span>
    <span></span>
  </header>
  <main>Main</main>
  <footer>Rodapé</footer>
</template>

<style>
@import "@/assets/base.css";

#app {
  max-width: 1280px;
  margin: 0 auto;
  font-weight: normal;
  height: 100vh;
}
header,
footer {
  height: 10%;
  background-color: rgb(246, 108, 104);
  color: rgb(238, 214, 214);
  font-size: 1.3rem;
  display: flex;
  align-items: center;
  padding-left: 20px;
}
main {
  height: 80%;
}
</style>
