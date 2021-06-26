<template>
  <div class="">
    <pre>
&lt;h1>Titulo descriptivo del contenido&lt;/h1>
&lt;h2>Titulo de la Gráfica&lt;/h2>

&lt;h2>Titulo de otra Gráfica&lt;/h2>
...

&lt;h3>Datos de la Gráfica&lt;/h3>
&lt;table>
  &lt;caption>De que van estos datos&lt;/caption>
  &lt;thead>
    &lt;tr>
      &lt;th scope="col">variable&lt;/th>
      &lt;th scope="col">variable&lt;/th>
      &lt;th scope="col">variable&lt;/th>
    &lt;/tr>
  &lt;/thead>
  &lt;body>
    &lt;tr>
      &lt;td scope="row">variable&lt;/td>
      &lt;td>valor&lt;/td>
      &lt;td>valor&lt;/td>
    &lt;/tr>
  &lt;/body>
&lt;/table>

    </pre>
    <a class="cite" href="https://www.a11yproject.com/posts/2016-03-05-accessible-data-tables/">
      A11y project
    </a>
  </div>
</template>

<script>
export default {
  name: 'Perceptible4'
}
</script>

<style lang="scss" scoped>
  .cite {
    display: block;
    margin-top: -36px;
    font-size: 16px;
  }
</style>
