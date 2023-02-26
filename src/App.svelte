<script>
  import { fade, fly } from 'svelte/transition';
  import { onMount } from 'svelte';

  let ready = false;
  onMount(() => ready = true);
</script>

<head>
  <link rel="stylesheet" href="https://pro.fontawesome.com/releases/v6.0.0-beta2/css/all.css">
</head>

{#if ready}
  <main>
    <div id="container">
      <span style="font-size: 18px;">
        <a href='https://discord.com/users/320002284186763264' class="social"><p id="discord" class="fab fa-discord mr-3 text-gray-500"></p></a>
        <a href="https://github.com/z4xi" class="social"><p id="github" class="fab fa-github mr-3 text-gray-500"></p></a>
        <a href="https://paypal.me/z4xi" class="social"><p id="paypal" class="fab fa-paypal text-gray-500"></p></a>
      </span>
        <h1>
        z4xi
      </h1>
      <p>
        professional <span style="color:#b6abff;">zestfest</span>
      </p>
      <img src="https://discord.c99.nl/widget/theme-4/320002284186763264.png" class="discord-thingy" />  
    </div>
  </main>
{/if}
