<template>
  <div class="">
    <pre>
&lt;html lang="es">
  &lt;h1>Gráficas super importantes&lt;/h1>
  &lt;h2>Mientras si son peras o manzanas&lt;/h2>
  &lt;ol lang="en" class="simple-bar-char">
    &lt;li>
      Pears &lt;span class="percent">(50%)&lt;/span>
    &lt;/li>
    &lt;li>
      Appples &lt;span class="percent">(50%)&lt;/span>
    &lt;/li>
  &lt;/ol>
  &lt;details>
    &lt;summary>Notas&lt;/summary>
    &lt;p>Información para entender la gráfica&lt;/p>
  &lt;/details>
  &lt;dl>
    &lt;dt>Término&lt;/dt>
    &lt;dd>Definición&lt;/dd>
    &lt;dt>Otro término&lt;/dt>
    &lt;dd>Definición&lt;/dd>
  &lt;/dl>
&lt;/html>
    </pre>
    <p class="note">
      Ejemplo de grafica con listas
      <a href="https://alistapart.com/article/accessibledatavisualization/">
        Wilson Miner: Accessible data visualization
      </a>
    </p>
  </div>
</template>

<script>
export default {
  name: 'Comprensible2'
}
</script>

<style lang="scss" scoped>
  .note {
    font-size: 16px;
    margin-top: -30px;
  }
</style>