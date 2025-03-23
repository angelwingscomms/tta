<script>
  import Navbar from '../components/Navbar.svelte';
</script>

<Navbar />

<main class="pt-20 min-h-screen bg-white dark:bg-gray-900">
  <div class="max-w-6xl mx-auto px-4">
    <h1 class="text-3xl font-bold text-gray-900 dark:text-gray-100 mb-8">Blog Posts</h1>
    <div class="space-y-4">
      <a 
        href="/christians-meeting-house-to-house" 
        class="block p-6 bg-gray-50 dark:bg-gray-800 rounded-lg shadow-sm hover:shadow-md transition-shadow"
      >
        <h2 class="text-xl font-semibold text-gray-900 dark:text-gray-100 mb-2">
          The Preacher Problem: Christians Gotta Hash Out Truth Together
        </h2>
        <p class="text-gray-600 dark:text-gray-400">
          Exploring why Christians should meet house-to-house and discuss scripture together...
        </p>
      </a>
    </div>
  </div>
</main>