<script>
  const links = ['a&b'];
</script>

<h1>page 1</h1>

{#each links as href}
  <a {href}>{href}</a>
{/each}
