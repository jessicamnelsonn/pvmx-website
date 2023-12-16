<section class="flex justify-center items-center flex-col min-h-screen bg-cover bg-center" style="background-image: url('images/pvmx-contact.jpg');">
  <div class="container mx-auto mt-8 p-8 bg-white rounded-lg shadow-lg max-w-md">
    <h1 class="text-3xl font-semibold text-center mb-6 text-teal-600">Contact Us</h1>

    <form action="#" method="post" class="space-y-4">
      <div>
        <label for="name" class="block text-sm font-medium text-gray-600">Full Name</label>
        <input type="text" id="name" name="name" placeholder="John Doe" class="mt-1 p-2 w-full border rounded-md focus:outline-none focus:ring focus:border-teal-500">
      </div>

      <div>
        <label for="email" class="block text-sm font-medium text-gray-600">Email Address</label>
        <input type="email" id="email" name="email" placeholder="john@example.com" class="mt-1 p-2 w-full border rounded-md focus:outline-none focus:ring focus:border-teal-500">
      </div>

      <div>
        <label for="message" class="block text-sm font-medium text-gray-600">Message</label>
        <textarea id="message" name="message" rows="4" placeholder="Your message..." class="mt-1 p-2 w-full border rounded-md focus:outline-none focus:ring focus:border-teal-500"></textarea>
      </div>

      <div>
        <label for="check-in" class="block text-sm font-medium text-gray-600">Check-In Date</label>
        <input type="date" id="check-in" name="check-in" class="mt-1 p-2 w-full border rounded-md focus:outline-none focus:ring focus:border-teal-500">
      </div>

      <div>
        <label for="check-out" class="block text-sm font-medium text-gray-600">Check-Out Date</label>
        <input type="date" id="check-out" name="check-out" class="mt-1 p-2 w-full border rounded-md focus:outline-none focus:ring focus:border-teal-500">
      </div>

      <button type="submit" class="bg-teal-500 text-white px-4 py-2 rounded-md hover:bg-teal-600 transition duration-300">
        Send Message
      </button>
    </form>
  </div>
</section>