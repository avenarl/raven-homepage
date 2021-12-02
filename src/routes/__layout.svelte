<style>
main {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}

div {
  flex: 1;
  margin-top: 4.5rem;
}

:global(html) {
  scroll-padding-top: 4.5rem;
}
</style>

<Navbar {segment} />
<main>
  <div>
    <slot />
  </div>
  <Footer />
</main>

<script lang="ts">
  import '../app.css';
  import Navbar from "$lib/components/Navbar.svelte"
  import Footer from "$lib/components/Footer.svelte"
  export let segment: string = "";
</script>
