<!-- <script>
  import { onMount } from 'svelte';
  
  let darkMode = true;
  
  onMount(() => {
    if (typeof window !== 'undefined') {
      darkMode = document.documentElement.classList.contains('dark');
    }
  });

  function toggleDarkMode() {
    darkMode = !darkMode;
    document.documentElement.classList.toggle('dark');
    if (typeof window !== 'undefined') {
      localStorage.setItem('darkMode', darkMode ? 'dark' : 'light');
    }
  }
</script>

<nav class="fixed top-0 left-0 right-0 bg-white dark:bg-gray-800 shadow-sm z-50">
  <div class="max-w-6xl mx-auto px-4">
    <div class="flex items-center justify-between h-16">
      <div class="flex space-x-4">
        <a href="/" class="text-gray-700 dark:text-gray-200 hover:text-indigo-600 dark:hover:text-indigo-400">Home</a>
        <a href="/christians-meeting-house-to-house" class="text-gray-700 dark:text-gray-200 hover:text-indigo-600 dark:hover:text-indigo-400">House to House</a>
      </div>
      <button
        on:click={toggleDarkMode}
        class="p-2 rounded-lg bg-gray-200 dark:bg-gray-700 text-gray-800 dark:text-gray-200"
        aria-label="Toggle dark mode"
      >
        {#if darkMode}
          🌙
        {:else}
          ☀️
        {/if}
      </button>
    </div>
  </div>
</nav> -->
<slot />