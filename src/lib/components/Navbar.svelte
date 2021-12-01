<style lang="postcss">
</style>

<nav class="navbar mb-2 shadow-lg bg-primary-focus text-base-300">
    <div class="px-2 mx-2 navbar-start">
      <span class="text-3xl font-bold"> Raven Rodrigo </span>
    </div>
    <div class="hidden px-2 mx-2 navbar-center lg:flex">
      <div class="flex items-stretch">
        <ul class="flex">
          <li class ="mr-6 text-xl" class:active={segment === "about"}>
            <a class="btn btn-ghost btn-sm rounded-btn" href="/about">About</a>
          </li>
          <li class="mr-6 text-xl" class:active={segment === "project"}>
            <a class="btn btn-ghost btn-sm rounded-btn" href="/project">Projects</a>
          </li>
          <li class="mr-6 text-xl" class:active={segment === "skills"}>
            <a class="btn btn-ghost btn-sm rounded-btn" href="/skills">Skills</a>
          </li>
          <li class="mr-6 text-xl" class:active={segment === "contact"}>
            <a class="btn btn-ghost btn-sm rounded-btn" href="/contact">Contact</a>
          </li>
        </ul>
      </div>
      <div class="navbar-end">
      </div>
    </div>

</nav>

<script lang="ts">

export let segment: string;

</script>
