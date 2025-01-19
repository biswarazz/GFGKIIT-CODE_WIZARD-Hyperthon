# GFGKIIT-CODE_WIZARD-Hyperthon
HackThon
<html lang="en">
 <head>
  <meta charset="utf-8"/>
  <meta content="width=device-width, initial-scale=1.0" name="viewport"/>
  <title>
   Spotify Clone
  </title>
  <script src="https://cdn.tailwindcss.com">
  </script>
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet"/>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&amp;display=swap" rel="stylesheet"/>
  <style>
   body {
            font-family: 'Roboto', sans-serif;
        }
  </style>
 </head>
 <body class="bg-gray-900 text-white">
  <!-- Sidebar -->
  <div class="flex">
   <div class="w-64 bg-gray-800 h-screen p-5">
    <div class="mb-8">
     <img alt="Spotify Logo" height="50" src="https://storage.googleapis.com/a1aa/image/ULWUkPA9CAoNNdnWyAYdwd3xG6yf1EgteqCtfHcgjxTbLLNoA.jpg" width="150"/>
    </div>
    <nav class="space-y-4">
     <a class="flex items-center space-x-2 text-gray-400 hover:text-white" href="#">
      <i class="fas fa-home">
      </i>
      <span>
       Home
      </span>
     </a>
     <a class="flex items-center space-x-2 text-gray-400 hover:text-white" href="#">
      <i class="fas fa-search">
      </i>
      <span>
       Search
      </span>
     </a>
     <a class="flex items-center space-x-2 text-gray-400 hover:text-white" href="#">
      <i class="fas fa-book">
      </i>
      <span>
       Your Library
      </span>
     </a>
    </nav>
    <div class="mt-10">
     <h3 class="text-gray-400 uppercase tracking-wider">
      Playlists
     </h3>
     <ul class="mt-4 space-y-2">
      <li>
       <a class="text-gray-400 hover:text-white" href="#">
        My Playlist #1
       </a>
      </li>
      <li>
       <a class="text-gray-400 hover:text-white" href="#">
        My Playlist #2
       </a>
      </li>
      <li>
       <a class="text-gray-400 hover:text-white" href="#">
        My Playlist #3
       </a>
      </li>
      <li>
       <a class="text-gray-400 hover:text-white" href="#">
        My Playlist #4
       </a>
      </li>
      <li>
       <a class="text-gray-400 hover:text-white" href="#">
        My Playlist #5
       </a>
      </li>
     </ul>
    </div>
   </div>
   <!-- Main Content -->
   <div class="flex-1 p-5">
    <header class="flex justify-between items-center mb-8">
     <div class="flex items-center space-x-4">
      <button class="text-gray-400 hover:text-white">
       <i class="fas fa-chevron-left">
       </i>
      </button>
      <button class="text-gray-400 hover:text-white">
       <i class="fas fa-chevron-right">
       </i>
      </button>
     </div>
     <div class="flex items-center space-x-4">
      <button class="bg-gray-700 text-white px-4 py-2 rounded-full">
       Upgrade
      </button>
      <img alt="User Profile Picture" class="rounded-full" height="40" src="https://storage.googleapis.com/a1aa/image/3egoa4LOSFzkZCxBmFY22mOO7cQE1ECZ5OeTELqcTdOsllGUA.jpg" width="40"/>
     </div>
    </header>
    <section class="mb-8">
     <h2 class="text-2xl font-bold mb-4">
      Recently Played
     </h2>
     <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-4">
      <div class="bg-gray-800 p-4 rounded-lg">
       <img alt="Album cover of Recently Played 1" class="mb-4 rounded-lg" height="300" src="https://storage.googleapis.com/a1aa/image/fvf9tHB4tGgqtEZumejdar0UPzjJ43sv3uGeuCFDwtv6WWaQB.jpg" width="300"/>
       <h3 class="text-lg font-semibold">
        Album Title 1
       </h3>
       <p class="text-gray-400">
        Artist Name 1
       </p>
      </div>
      <div class="bg-gray-800 p-4 rounded-lg">
       <img alt="Album cover of Recently Played 2" class="mb-4 rounded-lg" height="300" src="https://storage.googleapis.com/a1aa/image/gfeSKshUweTTqIFTx5zN7dDlE5wpahNXTQm6zzkDKQzxLLNoA.jpg" width="300"/>
       <h3 class="text-lg font-semibold">
        Album Title 2
       </h3>
       <p class="text-gray-400">
        Artist Name 2
       </p>
      </div>
      <div class="bg-gray-800 p-4 rounded-lg">
       <img alt="Album cover of Recently Played 3" class="mb-4 rounded-lg" height="300" src="https://storage.googleapis.com/a1aa/image/InfSPn7eumilNkfGSWJ1i1iLpq9k8IVv9APKsU7jvZonLLNoA.jpg" width="300"/>
       <h3 class="text-lg font-semibold">
        Album Title 3
       </h3>
       <p class="text-gray-400">
        Artist Name 3
       </p>
      </div>
      <div class="bg-gray-800 p-4 rounded-lg">
       <img alt="Album cover of Recently Played 4" class="mb-4 rounded-lg" height="300" src="https://storage.googleapis.com/a1aa/image/yHa3jJro7g7cM54qEz9ERREZM4Di984MLfbpnbVDFW06ySDKA.jpg" width="300"/>
       <h3 class="text-lg font-semibold">
        Album Title 4
       </h3>
       <p class="text-gray-400">
        Artist Name 4
       </p>
      </div>
     </div>
    </section>
    <section>
     <h2 class="text-2xl font-bold mb-4">
      Recommended for You
     </h2>
     <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-4">
      <div class="bg-gray-800 p-4 rounded-lg">
       <img alt="Album cover of Recommended 1" class="mb-4 rounded-lg" height="300" src="https://storage.googleapis.com/a1aa/image/LeWbTiaPBVQiGiANLIfqmaUU76BKWlbwlbkNcYIUmgu5llGUA.jpg" width="300"/>
       <h3 class="text-lg font-semibold">
        Album Title 5
       </h3>
       <p class="text-gray-400">
        Artist Name 5
       </p>
      </div>
      <div class="bg-gray-800 p-4 rounded-lg">
       <img alt="Album cover of Recommended 2" class="mb-4 rounded-lg" height="300" src="https://storage.googleapis.com/a1aa/image/V6fzuoaGDR1yE6dHRCu8HEecslWKknBE4VkSDiSPaYfgLLNoA.jpg" width="300"/>
       <h3 class="text-lg font-semibold">
        Album Title 6
       </h3>
       <p class="text-gray-400">
        Artist Name 6
       </p>
      </div>
      <div class="bg-gray-800 p-4 rounded-lg">
       <img alt="Album cover of Recommended 3" class="mb-4 rounded-lg" height="300" src="https://storage.googleapis.com/a1aa/image/m4aSsqJPCO69EtWuzJVWkfUq4Jg3c91lP4ImtFtI0kz7ySDKA.jpg" width="300"/>
       <h3 class="text-lg font-semibold">
        Album Title 7
       </h3>
       <p class="text-gray-400">
        Artist Name 7
       </p>
      </div>
      <div class="bg-gray-800 p-4 rounded-lg">
       <img alt="Album cover of Recommended 4" class="mb-4 rounded-lg" height="300" src="https://storage.googleapis.com/a1aa/image/tHpeNxkD9Z0KP6mcrZgjZdLuCRiibOIDk3NCjAMXBxu3ySDKA.jpg" width="300"/>
       <h3 class="text-lg font-semibold">
        Album Title 8
       </h3>
       <p class="text-gray-400">
        Artist Name 8
       </p>
      </div>
     </div>
    </section>
   </div>
  </div>
 </body>
</html>
