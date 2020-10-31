<template>
<footer class="text-gray-700 body-font bg-gray-200">
  <div class="container px-5 py-24 mx-auto flex md:items-center lg:items-start md:flex-row md:flex-no-wrap flex-wrap flex-col">
    <div class="w-64 flex-shrink-0 md:mx-0 mx-auto text-center md:text-left">
      <a class="flex title-font font-medium items-center md:justify-start justify-center text-gray-900">
        <svg xmlns="http://www.w3.org/2000/svg" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-10 h-10 text-white p-2 bg-teal-500 rounded-full" viewBox="0 0 24 24">
          <path d="M12 2L2 7l10 5 10-5-10-5zM2 17l10 5 10-5M2 12l10 5 10-5"></path>
        </svg>
        <span class="ml-3 text-xl">Online Store</span>
      </a>
      <p class="mt-2 text-sm text-gray-500">Lorem ipsum dolor sit amet consectetur adipisicing elit. Eaque, tempore aliquid inventore dignissimos eius optio! Rerum, quidem? Distinctio quasi, officia ea possimus, provident fugit autem maiores voluptas nesciunt odio fugiat.</p>
    </div>
    <div class="flex-grow flex flex-wrap md:pl-20 -mb-10 md:mt-0 mt-10 md:text-left text-center">
      <div class="lg:w-1/4 md:w-1/2 w-full px-4">
        <h2 class="title-font font-medium text-gray-900 tracking-widest text-sm mb-3">Layanan</h2>
        <nav class="list-none mb-10">
          <li>
            <a class="text-gray-600 hover:text-gray-800">Bantuan</a>
          </li>
          <li>
            <a class="text-gray-600 hover:text-gray-800">Product Index</a>
          </li>
          <li>
            <a class="text-gray-600 hover:text-gray-800">Hubungi Kami</a>
          </li>
        </nav>
      </div>
      <div class="lg:w-1/4 md:w-1/2 w-full px-4">
        <h2 class="title-font font-medium text-gray-900 tracking-widest text-sm mb-3">Tentang Kami</h2>
        <nav class="list-none mb-10">
          <li>
            <a class="text-gray-600 hover:text-gray-800">About Us</a>
          </li>
          <li>
            <a class="text-gray-600 hover:text-gray-800">Hubungi Kami</a>
          </li>
        </nav>
      </div>
      <div class="lg:w-1/4 md:w-1/2 w-full px-4">
        <h2 class="title-font font-medium text-gray-900 tracking-widest text-sm mb-3">Bantuan dan Panduan</h2>
        <nav class="list-none mb-10">
          <li>
            <a class="text-gray-600 hover:text-gray-800">Syarat dan Ketentuan</a>
          </li>
          <li>
            <a class="text-gray-600 hover:text-gray-800">Kebijakan Privasi</a>
          </li>
        </nav>
      </div>
    </div>
  </div>
</footer>
</template>

<script>
export default {
    name: 'Footer'
}
</script>