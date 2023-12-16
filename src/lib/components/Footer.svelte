<script>
  const navItems = [
    { name: 'Home', href: '/' },
    { name: 'About Us', href: '/about' },
    { name: 'Explore', href: '/explore' },
    { name: 'Contact', href: '/contact' },
  ];
</script>

<footer class="bg-[#cee3c1] py-4">
  <div class="container mx-auto flex flex-col items-center">
    <nav class="flex flex-wrap justify-center space-x-2 md:space-x-5 lg:space-x-8">
      {#each navItems as { name, href }}
        <a href={href} class="text-base md:text-lg lg:text-xl text-green-900 hover:text-green-700 hover:underline transition-colors duration-300 px-2 md:px-4 py-2 rounded-md focus:outline-none focus:shadow-outline">
          {name}
        </a>
      {/each}
    </nav>
    <p class="text-xs md:text-sm mt-4 text-green-900">&copy; 2023 PVMX</p>
  </div>
</footer>
