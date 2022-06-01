<template>
<header>
    <div class="menu-esquerdo">
      <span>Home</span>
      <span>|</span>
      <span>Jogadores</span>
      <span>|</span>
      <span>Times</span>
    </div>
    <div class="menu-direito">
      <span>Sair</span>
    </div>
  </header>
 <RouterView />
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
  background-color: rgb(50, 47, 224);
  color: white;
  font-size: 1.3rem;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding-left: 20px;
}
header span{
  padding:0 20px;
}
main {
  height: 80%;
}
</style>
