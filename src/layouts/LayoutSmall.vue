<script setup>
import SmallFooter from '@/components/templates/small/SmallFooter.vue'
import SmallHeader from '@/components/templates/small/SmallHeader.vue'
import SmallAside from '@/components/templates/small/SmallAside.vue'
</script>

<template>
<div id="layout-small" >
  <header>
    <small-header></small-header>
  </header>
  <aside>
    <small-aside></small-aside>
  </aside>
  <main>
    <router-view />
  </main>
  <footer>
    <small-footer></small-footer>
  </footer>
</div>
</template>
<style>
#layout-small {
  display: grid;
  grid-template-columns: 1fr 5fr;
  grid-template-rows: auto 1fr auto;
  grid-template-areas:
    'aside header'
    'aside main'
    'aside footer';
  min-height: 100vh;
}

header {
  display: flex;
 background-color: aquamarine;
  justify-content: flex-end;
  padding: 1.5rem;
  grid-area: header;
}
footer {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 3rem;
  background-color: #c24646;
  grid-area: footer;
}
aside {
  border-right: #c06c6c 1px solid;
  box-shadow: 0 0 10px 0 #5161bb;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  padding-top: 1.5rem;
  padding-bottom: 1.5rem;
  grid-area: aside;
  background-color: #a7adcf;
}
main {
  min-height: 80%;
  padding: 2rem;
  grid-area: main;
}
</style>