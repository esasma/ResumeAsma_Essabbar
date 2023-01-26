<script setup>
import { RouterLink, RouterView } from 'vue-router'

</script>
<template>
  <header class=" ">
    <nav class=" ">
      <div class="">
      <RouterLink to="/"><img src="" class="" alt="Logo du site"></RouterLink>
      <span class=" ">
        <MenuIcon class=" text-white"></MenuIcon>
      </span>
      </div>
      <ul class="" >
        <li>
          <RouterLink class=" " to="/">Home</RouterLink>
        </li>
        <li>
          <RouterLink class=" " to="/Programmation">Programmation</RouterLink>
        </li>
        <li>
          <RouterLink class=" " to="/Artistes">Artistes</RouterLink>
        </li>
        <li>
          <RouterLink class=" " to="/Festival">Festival</RouterLink>
        </li>
        <li>
          <RouterLink class=" " to="/Contact">Contact</RouterLink>
        </li>
      </ul>
    </nav>
  </header>
    <Router-View />

</template>

<script>
import { MenuIcon, } from "@heroicons/vue/solid";


export default {
  name: "App",
  components: { MenuIcon,},
};

</script>


