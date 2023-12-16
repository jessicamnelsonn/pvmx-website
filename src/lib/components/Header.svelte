<script>
  const navItems = [
    { name: 'Home', href: '/' },
    { name: 'About Us', href: '/about' },
    { name: 'Explore', href: '/explore' },
    { name: 'Contact', href: '/contact' },
  ];
</script>

<header>
  <nav class="bg-[#cee3c1] py-4 flex flex-wrap items-center justify-between">
    <div class="flex items-center">
      <img src="/images/pvmx-logo.png" alt="Logo" class="h-9 w-14 mr-4">
    </div>

    <ul class="flex items-end space-x-2 md:space-x-5 lg:space-x-8">
      {#each navItems as { name, href }}
        <li>
          <a href={href} class="text-base md:text-lg lg:text-xl text-green-900 hover:text-green-600 hover:underline transition-colors duration-300 px-2 md:px-3 py-2 rounded-md focus:outline-none focus:shadow-outline">
            {name}
          </a>
        </li>
      {/each}
    </ul>
  </nav>
</header>
