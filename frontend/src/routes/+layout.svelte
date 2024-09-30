<script>
    import "../app.css";
    import Navbar from "$lib/components/Navbar/navbar.svelte";
  </script>

<div class="flex gap-5">
  <Navbar />

  <slot />
</div>
  