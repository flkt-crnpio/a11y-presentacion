<template>
  <div class="">
    <h2>
      <span class="a11y">a<span class="color">11</span>y</span>
      <span class="accessibility">a<span class="color">ccessibilit</span>y</span>
    </h2>
    <p>
      La accesibilidad web se enfoca en las diferencias que afectan o
      pueden hacer dificil el acceso a las herramientas en internet.
    </p>
    <ul>
      <li>Visuales</li>
      <li>Auditivas</li>
      <li>Físicas</li>
      <li>Cognitivas</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'Pagina4'
}
</script>

<style lang="scss" scoped>
  h2 {
    letter-spacing: .3em;
  }
  .color {
    display: inline-block;
    margin: 0 10px;
    opacity: .7;
  }
  .accessibility {
    text-transform: uppercase;
    font-size: .7em;
  }
  .a11y {
    display: block;
    padding-left: 80px;
  }
</style>
