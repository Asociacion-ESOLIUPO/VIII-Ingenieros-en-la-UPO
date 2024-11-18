<template>
  <div class="main-header">
    <h1>VIII Jornadas Ingenieros en la UPO</h1>
    <nav class="main-header--navbar">
      <ul>
        <li><a href="/">Inicio</a></li>
        <li><a href="/about">Quiénes somos</a></li>
        <li><a href="/ingenierosUpo">¿Qué es el Ingenieros en la UPO?</a></li>
        <li><a href="/entradas">Sobre las entradas</a></li>
        <li><a href="/evento">¿En qué consiste el evento?</a></li>
        <li>
          <a href="/organizadoresYapoyo">Organizadores y Apoyo Institucional</a>
        </li>
        <li><a href="/impacto">Nuestro Impacto</a></li>
        <li><a href="/patrocinios">Patrocinadores</a></li>
        <li>
          <a href="inversionPatrocinio">¿En qué invertiremos el patrocinio?</a>
        </li>
        <li><a href="/contact">Contact</a></li>
      </ul>
    </nav>
  </div>
</template>

<script setup></script>

<style scoped>
.main-header {
  background-color: #f0f0f0;
  padding: 20px;
  text-align: center;
}

.main-header--navbar ul {
  list-style: none;
  padding: 0;
}

.main-header--navbar li {
  display: inline;
  margin: 0 10px;
}

.main-header--navbar a {
  text-decoration: none;
  color: #333;
}
</style>
