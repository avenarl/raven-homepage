<style>
.header {
 max-width: 1080px;
 grid-template-columns: 20rem 1fr;
 margin: 5rem auto;
}
.header-name {
  font-size: clamp(1.25rem, calc(5vw + 1.25rem), 3rem);
  line-height: 1.25em;
}
.header-role {
  font-size: clamp(1rem, calc(5vw + 0.5rem), 1.625rem);
}
.header-desc {
  font-size: clamp(0.8rem, calc(2vw + 0.5rem), 1.125rem);
}
.icons {
  margin: 3rem auto 0.5rem;
}
.icons a {
  transition: ease-out 0.2s;
}
.icons a:hover {
  color: #8A00FC;
}

</style>
<section class="header mt-10 my-2 my-auto">
  <div class="relative">
    <span class="text-2xl font-medium text-accent">Hi there!</span>
    <span class="header-name relative block font-semibold leading-5 my-1"> I'm Raven 
    Carlos T. Rodrigo. </span>
    <span class="header-role block leading-5 my-3">
      A software developer with passion in graphic design and software engineering!
    </span>
    <span class="header-desc relative block leading-5 mx-0 mb-8 italic text-neutral-focus">
      I like to write code and learn more about software engineering, and sometimes I do graphic design. I love unix operating systems, vim/neovim and adobe illustrator. Feel free to message me!
    </span>
    <div class="icons">
        <ul class="flex">
          <li class ="mr-10">
            <a target="_blank" 
               href="https://www.linkedin.com/in/ravenrodrigo/">
              <Linkedin />
            </a> 
          </li>
          <li class="mr-10">
            <a target="_blank" href="https://github.com/avenarl">
              <Github />
            </a>
          </li>
          <li class="mr-10">
            <a target="_blank" href="https://stackoverflow.com/users/12834452/avenarl?tab=profile">
              <Stackoverflow />
            </a>
          </li>
          <li class="mr-10">
            <a target="_blank" href="https://www.behance.net/ravenrodrigo">
              <Behance />
            </a>
          </li>
        </ul>
      <button class="btn btn-accent mt-8 hover:btn-accent hover:bg-accent-focus">
      <a target="_blank" href="../../static/assets/resume/Raven_Rodrigo(Resume).pdf"> Download Resume </a>
    </button> 
    </div>
  </div>
</section>

<script>
import data from "$lib/data/site";
import Github from "$lib/icons/Github.svelte";
import Linkedin from "$lib/icons/Linkedin.svelte";
import Stackoverflow from "$lib/icons/Stackoverflow.svelte";
import Behance from "$lib/icons/Behance.svelte";
const { github, linkedin, stackoverflow, behance } = data;
</script>
