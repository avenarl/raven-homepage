<style lang="postcss">
 .item {
     @apply text-lg text-gray-600;
   }
</style>

<nav class="navbar">
  <div class="container">
    <div class="title">
      <a href="/" aria-label="logo">Raven</a>
    </div>
    <ul class="items">
      <li class="item" class:active={segment === "about"}>
        <a href="/about">About</a>
      </li>
      <li class="item" class:active={segment === "project"}>
        <a href="/project">Projects</a>
      </li>
      <li class="item" class:active={segment === "skills"}>
        <a href="/skills">Skills</a>
      </li>
      <li class="item" class:active={segment === "contact"}>
        <a href="/contact">Contact</a>
      </li>
    </ul>
  </div>

</nav>

<script lang="ts">

export let segment: string;

</script>
