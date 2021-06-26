<template>
  <div class="">
    <h3>Accesible al teclado</h3>
    <pre>
&lt;svg
  // hace al elemento accesible
  tabindex="0" 

  // e interactivo
  role="application" 
  
  // descripción para lectores de pantalla
  aria-roledescription="descripción" 
  
  // vínculo con su titulo
  aria-labelledby="histogram-title"
>
  ...bars
  &lt;g id="axis" aria-hidden="true" />
&lt;/svg>

&lt;figcaption id="histogram-title">
  Título descriptivo del histograma
&lt;/figcaption>
    </pre>
    <cite href="https://blog.interactivethings.com/how-does-this-data-sound-945ed27a1a95">
      <small>Luc Guillemot: How Does This Data Sound?</small>
    </cite>
  </div>
</template>

<script>
export default {
  name: 'Robusto3'
}
</script>
