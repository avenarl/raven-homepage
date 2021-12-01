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
        <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
          <path fill-rule="evenodd" d="M10 2a1 1 0 011 1v1a1 1 0 11-2 0V3a1 1 0 011-1zm4 8a4 4 0 11-8 0 4 4 0 018 0zm-.464 4.95l.707.707a1 1 0 001.414-1.414l-.707-.707a1 1 0 00-1.414 1.414zm2.12-10.607a1 1 0 010 1.414l-.706.707a1 1 0 11-1.414-1.414l.707-.707a1 1 0 011.414 0zM17 11a1 1 0 100-2h-1a1 1 0 100 2h1zm-7 4a1 1 0 011 1v1a1 1 0 11-2 0v-1a1 1 0 011-1zM5.05 6.464A1 1 0 106.465 5.05l-.708-.707a1 1 0 00-1.414 1.414l.707.707zm1.414 8.486l-.707.707a1 1 0 01-1.414-1.414l.707-.707a1 1 0 011.414 1.414zM4 11a1 1 0 100-2H3a1 1 0 000 2h1z" clip-rule="evenodd" />
        </svg>
      </div>
    </div>

</nav>

<script lang="ts">

export let segment: string;

</script>
