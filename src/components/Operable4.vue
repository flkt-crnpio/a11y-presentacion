<template>
  <div class="">
    <h2><br></h2>
    <pre>
&lt;script>
arcGroup
  ... 
  .attr('tabindex', 0) // para darle foco

  .attr('aria-describedby',
    (d, i) => `tooltip-${i}`) 

  .on('mouseenter',// actualiza aria-describedby

  .on('mouseleave',// elimina aria-describedby

tooltipGroup
  .selectAll('.tooltip-item')
  .data(data)
  .enter()
  .append('g')
  .attr('id', (d, i) => `tooltip-${i}`)
&lt;/script>
    </pre>
    <a href="https://www.a11ywithlindsey.com/blog/accessibility-d3-donut-charts">
      Lindsey: Accessibility d3 donut charts
    </a>
  </div>
</template>

<script>
export default {
  name: 'Operable4'
}
</script>
