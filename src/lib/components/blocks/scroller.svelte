<script>
    import FirstSvg from '$lib/img/scroll-text-color.svelte';
    import SecondSvg from '$lib/img/scroll-text-dark.svelte';
  </script>
  
  <div class="relative overflow-hidden whitespace-nowrap h-20">
    <div class="flex animate-scroll-svg">
      <div class="inline-block mr-30">
        <FirstSvg />
      </div>
      <div class="inline-block mr-30">
        <SecondSvg/>
      </div>
      <!-- Repeat SVGs to ensure continuous scrolling -->
      <div class="inline-block mr-30">
        <FirstSvg />
      </div>
      <div class="inline-block mr-30">
        <SecondSvg/>
      </div>
    </div>
  </div>
  