  <Navbar {segment} />

<main>
  <slot></slot>
</main>

<script lang="ts">
  import Navbar from "$lib/components/Navbar.svelte"

  export let segment: string = "";
</script>
