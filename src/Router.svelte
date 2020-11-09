<script>
  import Home from './Home/index.svelte'

  const path = window.location.pathname
</script>

{#if path === '/'}
  <Home />
{/if}
