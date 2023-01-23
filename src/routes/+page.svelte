<script>
  import Icon from 'svelte-awesome';
  import { github, linkedin, twitter,} from 'svelte-awesome/icons';
</script>

<div class=" container mx-auto">
  <div class="bg-slate-dark-gray mx-16 h-screen flex flex-row justify-between">
    <div class="fixed top-0 z-10 mx-8">
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
    
   <div class="flex-1 ml-16">
    <p class="text-white text-2xl"> this is a starting point </p>
   </div>
  </div>
</div>

  
  <style lang="postcss">
    :global(html) {
      background-color: theme(colors.black);
    }
  </style>