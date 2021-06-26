<template>
  <div class="">
    <h3>Interacción con el teclado</h3>
    <pre>
&lt;svg
  // para lectores de pantalla
  // indica que el elemento hijo
  // recive el foco
  aria-activedescendant="histogram-bar-1"

  // pero para que lean la etiqueta
  // se asigna el foco en código
  onkeydown="moveFocusToDataPoint()"
>

function moveFocusToDataPoint() {
  document
    .getElementById("histogram-bar-1")
    .focus();
}
    </pre>
    <cite href="https://blog.interactivethings.com/how-does-this-data-sound-945ed27a1a95">
      <small>Luc Guillemot: How Does This Data Sound?</small>
    </cite>
  </div>
</template>

<script>
export default {
  name: 'Robusto4'
}
</script>
