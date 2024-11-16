vue
<template>
  <header>
    <h1>VIII Jornadas Ingenieros en la UPO</h1>
    <nav>
      <ul>
        <li><a href="/">Inicio</a></li>
        <li><a href="/about">Quiénes somos</a></li>
        <li><a href="/ingenierosUpo">¿Qué es el Ingenieros en la UPO?</a></li>
        <li><a href="/entradas">Sobre las entradas</a></li>
        <li><a href="/evento">¿En qué consiste el evento?</a></li>
        <li><a href="/organizadoresYapoyo">Organizadores y Apoyo Institucional</a></li>
        <li><a href="/impacto">Nuestro Impacto</a></li>
        <li><a href="/patrocinios">Patrocinadores</a></li>
        <li><a href="inversionPatrocinio">¿En qué invertiremos el patrocinio?</a></li>
        <li><a href="/contact">Contact</a></li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
  name: 'Header'
}
</script>

<style scoped>
header {
  background-color: #f0f0f0;
  padding: 20px;
  text-align: center;
}

nav ul {
  list-style: none;
  padding: 0;
}

nav li {
  display: inline;
  margin: 0 10px;
}

nav a {
  text-decoration: none;
  color: #333;
}
</style>
