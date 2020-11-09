<script>
  import Layout from "./Layout/index.svelte";
  import Router from "./Router.svelte";
</script>

<style global lang="postcss">
  /* only apply purgecss on utilities, per Tailwind docs */
  /* purgecss start ignore */
  @tailwind base;
  @tailwind components;
  /* purgecss end ignore */

  @tailwind utilities;

  @layer base {
    body {
      @apply h-screen w-screen;
    }
  }
</style>

<Layout>
  <Router />
</Layout>
