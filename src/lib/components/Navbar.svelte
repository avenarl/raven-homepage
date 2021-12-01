<style lang="postcss">
</style>

<nav class="navbar mb-2 shadow-lg bg-neutral text-neutral-content">
  <div class="navbar-container">
    <div class="px-2 mx-2 navbar-start">
      <span class="text-lg font-bold"> CODERAVEN </span>
    </div>
    <ul class="flex">
      <li class ="mr-6" class:active={segment === "about"}>
        <a class="text-blue-500 hover:text-blue-800" href="/about">About</a>
      </li>
      <li class="mr-6" class:active={segment === "project"}>
        <a class="text-blue-500 hover:text-blue-800" href="/project">Projects</a>
      </li>
      <li class="mr-6" class:active={segment === "skills"}>
        <a class="text-blue-500 hover:text-blue-800" href="/skills">Skills</a>
      </li>
      <li class="mr-6" class:active={segment === "contact"}>
        <a class="text-blue-500 hover:text-blue-800" href="/contact">Contact</a>
      </li>
    </ul>
  </div>

</nav>

<script lang="ts">

export let segment: string;

</script>
