<template>

<div>
  <h3 class="sample">
    <span class="color">&lt;img alt="</span>chart-type
    <span class="color"> of </span>type-of-data
    <span class="color"> where </span>reason-for-include-chart
    <span class="color">" /></span>
  </h3>
  <a class="cite" href="https://medium.com/nightingale/writing-alt-text-for-data-visualization-2a218ef43f81">
    Amy Cesal
  </a>
  <pre>
&lt;figure role="group">
  &lt;img src="grafica.jpg"
    alt="Gráfica de barras 
    de datos comparativos de covid
    en donde se observa..." 
    longdesc="#chart-longdesc" /> 
  &lt;figcaption>
    &lt;p>Fuente de datos:
      Nombre de la fuente. Fecha.
      &lt;a href="datos.zip" 
        download="nombre-doc.zip">
        Nombre de los datos.
        CSV y Nota metodológica.
        Peso: 12.3 MB
      &lt;/a>
    &lt;/p>
  &lt;/figcaption>
&lt;/figure>
&lt;div id="chart-longdesc">
  ...
&lt;/div>
  </pre>
  <a class="cite m--t" href="https://www.w3.org/WAI/tutorials/images/complex/">
    WAI Imágenes complejas
  </a>
</div>
</template>

<script>
export default {
  name: 'Perceptible2'
}
</script>

<style lang="scss" scoped>
  .color {
    opacity: .7;
  }
  .cite {
    display: block;
    font-size: 16px;
  }
  .m--t {
    margin-top: -36px;
  }
  pre {
    white-space: pre-wrap;
  }
  .sample {
    margin-bottom: 0;
  }
  @media only screen and (min-width: 769px) {
    .mt {
      margin-top: 70px;
    }
  }
</style>
