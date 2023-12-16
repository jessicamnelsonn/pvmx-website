<script>
  const navItems = [
    { name: 'Home', href: '/home' },
    { name: 'About Us', href: '/about' },
    { name: 'Explore', href: '/explore' },
    { name: 'Contact', href: '/contact' },
  ];
</script>

<nav class="bg-blue-500 py-4">
  <div class="container">
    <ul class="flex items-center space-x-5 md:space-x-8">
      {#each navItems as { name, href }}
        <li>
          <a href={href} class="text-lg md:text-xl lg:text-2xl text-white hover:text-indigo-100 hover:underline transition-colors duration-300 px-3 py-2 rounded-md focus:outline-none focus:shadow-outline">
            {name}
          </a>
        </li>
      {/each}
    </ul>
  </div>
</nav>
