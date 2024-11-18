<template>
  <div class="main-header">
    <h1>VIII Jornadas Ingenieros en la UPO</h1>
    <nav class="main-header--navbar">
      <ul>
        <li v-for="item in headerItems" :key="item.href">
          <a :href="item.href">{{ item.text }}</a>
        </li>
      </ul>
    </nav>
  </div>
</template>

<script setup>
import { ref } from "vue";

let headerItems = ref([
  { href: "/", text: "Inicio" },
  { href: "/about", text: "Quiénes somos" },
  { href: "/ingenierosUpo", text: "¿Qué es el Ingenieros en la UPO?" },
  { href: "/entradas", text: "Sobre las entradas" },
  { href: "/evento", text: "¿En qué consiste el evento?" },
  { href: "/organizadoresYapoyo", text: "Organizadores y Apoyo Institucional" },
  { href: "/impacto", text: "Nuestro Impacto" },
  { href: "/patrocinios", text: "Patrocinadores" },
  { href: "/inversionPatrocinio", text: "¿En qué invertiremos el patrocinio?" },
  { href: "/contact", text: "Contact" },
]);
</script>

<style scoped>
.main-header {
  background-color: #f0f0f0;
  padding: 20px;
  text-align: center;
}

.main-header--navbar {
  margin-top: 20px;
}

.main-header--navbar ul {
  display: flex;
  list-style: none;
  padding: 0;
}

.main-header--navbar li {
  display: inline;
  padding: 3px;
  margin: 0 10px;
}

.main-header--navbar a {
  text-decoration: none;
  color: #333;
}
</style>
