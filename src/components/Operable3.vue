<template>
  <div class="">
    <h2><br></h2>
    <h3>Navegación por teclado</h3>
    <p>
      Para los elementos que no tienen un tag semantico
      se debe utilizar Accessible Rich Internet Applications (ARIA)
      para agregar roles y propiedades a los elementos
      y hacerlos mas accesibles a personas con discapacidades.<br>
    </p>

    <a href="https://w3c.github.io/using-aria/">Reglas para utilizar ARIA</a>
    <ol>
      <li>Primero intenta utilizar elementos nativos</li>
      <li>No cambies semanticas nativas con ARIA</li>
      <li>Todos los controles interactivos deben poder ser utilizados con el teclado</li>
      <li>
        No utilizar <code>role="presentation"</code>
        no <code>aria-hiden="true"</code> en elementos que tienen focus nativo.
        (como botones o links)
      </li>
      <li>Todos los elementos interactivos deben tener nombre</li>
    </ol>
  </div>
</template>

<script>
export default {
  name: 'Operable3'
}
</script>
