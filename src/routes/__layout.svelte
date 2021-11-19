  <Navbar {segment} />

<main>
  <slot></slot>
  <Footer />
</main>

<script lang="ts">
  import Navbar from "$lib/components/Navbar.svelte"
  import Footer from "$lib/components/Footer.svelte"
  export let segment: string = "";
</script>
