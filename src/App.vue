<script setup>
import CamphersAD from './views/CamphersAD.vue'
import './common/font/font.css'
</script>

<template>
  <CamphersAD />
</template>

<style>
#app {
  font-family: 'MiSans';
}

/* scrollbar style */
::-webkit-scrollbar {
  background-color: transparent;
  width: 6px;
}

::-webkit-scrollbar-thumb {
  background-color: #cfd6df;
  border-radius: 10px;
  -webkit-box-shadow: none;
}

::-webkit-scrollbar-track {
  background-color: transparent;
  border-radius: 10px;
  -webkit-box-shadow: none;
}

:hover::-webkit-scrollbar-thumb {
  background-color: #c5cbd4;
}
</style>
