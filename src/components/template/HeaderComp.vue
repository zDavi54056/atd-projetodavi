<template>
  <header>
    <div class="menu-esquerdo">
      <span><RouterLink to="/">Home</RouterLink></span>
      <span>|</span>
      <span><RouterLink to="/Jogadores">Jogadores</RouterLink></span>
      <span>|</span>
       <span><RouterLink to="/Times">Times</RouterLink></span>
    </div>
    <div class="menu-direito">
      <span>Sair</span>
    </div>
  </header>
</template>

<style>
header {
  height: 10%;
  background-color: black;
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
</style>