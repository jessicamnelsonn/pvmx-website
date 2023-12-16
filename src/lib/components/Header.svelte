<script>
  const navItems = [
    { name: 'Home', href: '/' },
    { name: 'About Us', href: '/about' },
    { name: 'Explore', href: '/explore' },
    { name: 'Contact', href: '/contact' },
  ];
</script>

<header>
  <nav class="bg-[#cee3c1] py-4 flex justify-end">
    <div class="flex-shrink-0 ml-4">
      <img src="your-logo.png" alt="Logo" class="h-8 w-8">
    </div>

    <ul class="flex items-end space-x-5 md:space-x-8 ml-auto">
      {#each navItems as { name, href }}
        <li>
          <a href={href} class="text-lg md:text-xl lg:text-2xl text-green-900 hover:text-green-600 hover:underline transition-colors duration-300 px-3 py-2 rounded-md focus:outline-none focus:shadow-outline">
            {name}
          </a>
        </li>
      {/each}
    </ul>
  </nav>
</header>
