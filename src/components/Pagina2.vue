<template>
  <div class="mt">
    <figure role="group">
      <blockquote>
        The power of the Web is in its universality. 
        Access by everyone regardless of disability is an essential aspect.
      </blockquote>
      <figcaption>Tim Berners-Lee inventor de la World Wide Web</figcaption>
    </figure>
  </div>
</template>

<script>
export default {
  name: 'Pagina2'
}
</script>

<style lang="scss" scoped>
  blockquote {
    padding: 0;
    margin: 0;
    font-size: 26px;
    font-weight: bold;
  }
  figcaption {
    margin: 20px;
    font-style: italic;
  }
  @media only screen and (min-width: 769px) {
    .mt {
      margin-top: 100px;
    }
  }
</style>
