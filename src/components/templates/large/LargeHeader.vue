<template>
  <div class="NavbarPropaganda">
    <nav class="NavbarItemsPropaganda">
    </nav>
    <nav class="NavbarItemsPropaganda NavbarItemsRight">
      <div class="NavbarLink">
        Entrar
      </div>
    </nav>
  </div>

  <div class="Navbar">
    <nav class="NavbarItems">
      <div class="NavbarTitle">
        Crocant
      </div>
      <div class="NavbarLink">
        Feminino
      </div>
      <div class="NavbarLink">
        Masculino
      </div>
      <div class="NavbarLink">
        Infantil
      </div>
      <div class="NavbarLink">  
        Pins
      </div>
      <div class="NavbarLink">
        ProTrabalho
      </div>
    </nav>

  </div>
  <hr>
</template>
<style scoped>
.NavbarPropaganda {
  background-color: #864EFF;
  display: flex;
  padding: 7px;
  font-family: sans-serif;
  color: #fff;

}

.NavbarItemsPropaganda {
  display: flex;
}

.NavbarLinkPropaganda {
  padding-right: 8px;
}

.NavbarItemsRightPropaganda {
  margin-left: auto;
}

hr {
  background-color: #864EFF;
  padding: 3px;
}

.Navbar {
  background-color: #fff;
  display: flex;
  padding: 16px;
  font-family: sans-serif;
  color: #864EFF;

}

.NavbarItems {
  display: flex;
}

.NavbarLink {
  margin-right: 10%;
  margin-left: 20%;
  font-size: x-large;
}

.NavbarItemsRight {
  margin-left: auto;
}

.NavbarTitle {
  margin-right: 8px;
  font-family: 'Cherry Bomb One';
  font-size: x-large;
}
</style>