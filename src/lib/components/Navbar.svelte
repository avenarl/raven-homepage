<style lang="postcss">
 .btn-ghost:hover {
   background-color: #8A00FC;
   color: #fff;
   }
</style>

<nav class="navbar mb-2 shadow-md  text-primary-focus p-2 mt-0 fixed w-full z-10 top-0 bg-opacity-50 ">
    <div class="px-2 mx-24 navbar-start">
      <a class="text-3xl text-black font-bold hover:text-accent" href="/"> avenarl </a>
    </div>
    <div class="hidden px-2 mx-24 navbar-center xl:flex">
      <div class="flex items-stretch">
        <ul class="flex">
          <li class="mr-1 text-2xl" class:active={segment === "home"}>
            <a class="btn btn-ghost btn-md rounded-btn" href="/">Home</a>
          </li>
          <li class ="mr-1 text-2xl" class:active={segment === "about"}>
            <a class="btn btn-ghost btn-md rounded-btn" href="/about">About</a>
          </li>
          <li class="mr-1 text-2xl" class:active={segment === "project"}>
            <a class="btn btn-ghost btn-md rounded-btn" href="/project">Projects</a>
          </li>
          <li class="mr-1 text-2xl" class:active={segment === "skills"}>
            <a class="btn btn-ghost btn-md rounded-btn" href="/skills">Skills</a>
          </li>
          <li class="mr-1 text-2xl" class:active={segment === "contact"}>
            <a class="btn btn-ghost btn-md rounded-btn" href="/contact">Contact</a>
          </li>
        </ul>
      </div>
      <div class="navbar-end">
       <button class="btn btn-accent hover:bg-gray-700 hover:border-gray-700">
          <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
            <path d="M17.293 13.293A8 8 0 016.707 2.707a8.001 8.001 0 1010.586 10.586z" />
          </svg>
       </button>
      </div>
    </div>
</nav>

<script lang="ts">

export let segment: string;

</script>
