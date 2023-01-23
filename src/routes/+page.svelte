<script>
  import Icon from 'svelte-awesome';
  import { github, linkedin, twitter,} from 'svelte-awesome/icons';
  import Nav from '$lib/components/nav.svelte';
</script>

<div class="container mx-auto">
  <div class="fixed bg-slate-dark-gray flex flex-row justify-between container mx-auto">
    <div class="top-0 z-10 mx-8">
      <div class="flex flex-col justify-center items-center text-center text-slate-light-gray">
        <div class="w-px h-44 bg-slate-light-gray"></div>
        <a href="https://linkedin.com" class="my-1 text-2xl  hover:text-white">
          <Icon data={github} scale={1.5}/>
        </a>
        <a href="https://github.com" class="my-1 text-2xl  hover:text-white">
          <Icon data={linkedin} scale={1.5}/>
        </a>
        <a href="https://twitter.com" class="my-1 text-2xl  hover:text-white">
          <Icon data={twitter} scale={1.5}/>
        </a>
      </div>
    </div>
    <Nav/>
  </div>
</div>

  
  <style lang="postcss">
    :global(html) {
      background-color: theme(colors.black);
    }
  </style>