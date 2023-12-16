<script>
  const navItems = [
    { name: 'Home', href: '/' },
    { name: 'About Us', href: '/about' },
    { name: 'Explore', href: '/explore' },
    { name: 'Contact', href: '/contact' },
  ];
</script>

<footer class="bg-[#cee3c1] py-4">
    <nav class="flex justify-center">
      {#each navItems as { name, href }}
        <a href={href} class="text-lg md:text-xl lg:text-2xl text-green-900 hover:text-green-700 hover:underline transition-colors duration-300 px-5 py-2 rounded-md focus:outline-none focus:shadow-outline">
          {name}
        </a>
      {/each}
    </nav>
    <p class="flex justify-center text-sm mt-4 text-green-900">&copy; 2023 PVMX</p>
</footer>
