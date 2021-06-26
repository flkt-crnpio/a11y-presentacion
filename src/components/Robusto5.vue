<template>
  <div class="">
    <h3>...interacción con el teclado</h3>
    <p>Agregar interacción a las barras del histograma</p>
    <pre>
&lt;rect
  id="histogram-bar-1"

  // para que pueda recibir foco
  tabindex="1"

  // vincular id del tooltip
  aria-labelledby="histogram-tooltip-1" 

  onkeydown="moveFocusToNextDataPoint()"
/>

&lt;div
  role="tooltip" 
  id="histogram-tooltip-1"
>
  Información para mostrar
  cuando la barra este en foco
&lt;/div>

    </pre>
    <cite href="https://blog.interactivethings.com/how-does-this-data-sound-945ed27a1a95">
      <small>Luc Guillemot: How Does This Data Sound?</small>
    </cite>
  </div>
</template>

<script>
export default {
  name: 'Robusto5'
}
</script>
