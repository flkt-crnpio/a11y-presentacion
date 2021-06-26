<template>
  <div class="">
    <pre>
&lt;head>
  &lt;meta name="viewport" 
  content="width=device-width,initial-scale=1.0">
  ...
  &lt;style>
    img { width: 100%; }

    @media only screen and (min-width: 1024px) {
      .container { display: flex; }
      img { width: 60%; }
    }
  &lt;/style>
&lt;/head>

&lt;body>
  &lt;div class="container">
    &lt;img src="grafica.png" 
      alt="descripción general de la gráfica"
      aria-describedby="info1"/>
    &lt;p id="info1">
      La descripción extensa de la gráfica
    &lt;/p>
  &lt;/div>
&lt;/body>
    </pre>
  </div>
</template>

<script>
export default {
  name: 'Robusto2'
}
</script>
