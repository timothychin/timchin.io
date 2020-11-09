<script>
  import Navbar from "../Navbar/index.svelte";
</script>

<div class="max-h-screen flex justify-center">
  <div class="h-full md:w-1/2">
    <Navbar />
    <slot />
  </div>
</div>
