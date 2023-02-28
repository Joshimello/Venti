<body class="h-screen flex flex-col justify-center items-center">
  
  <div class="flex gap-8 text-6xl font-serif text-stroke-1 text-stroke-white">
    {#each 'VENTI' as t}
      <span>{t}</span>
    {/each}
  </div>

  <div>
    <div class="text-lg font-mono absolute">
      VITE SVELTE TYPESCRIPT WINDICSS
    </div>
    <div class="text-lg font-mono text-white text-stroke-2 text-stroke-white">
      VITE SVELTE TYPESCRIPT WINDICSS
    </div>
  </div>

  <img 
    class="absolute h-72 pb-8 -z-1 opacity-70"
    src="/venti.jpg"
  >

</body>