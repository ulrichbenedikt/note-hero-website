<!-- app.vue -->
<template>
  
  <main class="min-h-screen bg-black text-white">
    <img src="/background.png" alt="Note Hero Logo" class="object-cover h-screen w-full absolute opacity-15"/>
    <div class="relative flex flex-col items-center justify-center px-4 py-12 min-h-screen">
      <img src="/logo.png" alt="Note Hero Logo" class="w-32 h-32 mb-6" />
      <h1 class="text-4xl font-bold mb-4">Note Hero</h1>
      <p class="text-lg text-center max-w-md mb-8">
        A minimalist note app for focused thinking. Markdown, client linking, shortcuts, and more. 
      </p>
      <div class="flex flex-col gap-4 sm:flex-row ">
        <a
          href="https://kdrive.infomaniak.com/app/share/1638485/c52b7228-8162-42d3-b7ad-1750453426d9"
          download
          style="background: linear-gradient(235deg,rgba(253, 29, 29, 1) 0%, rgba(252, 69, 203, 1) 100%);"
          class="bg-white text-white px-6 py-3 rounded-xl opacity-80 hover:opacity-100 transition"
        >
          Download for macOS<sup>1</sup><br /><span class="text-xs">Version 1.1.0</span>
        </a>
        <a
          href="https://kdrive.infomaniak.com/app/share/1638485/9acdd6c3-3aa1-4c30-a15b-e08e7db4645a"
          target="_blank"
          download
          style="background: linear-gradient(203deg,rgba(230, 23, 23, 1) 0%, rgba(245, 108, 208, 1) 100%);"
          class="text-white px-6 py-3 rounded-xl opacity-80 hover:opacity-100  transition"
        >
          Download for Windows<sup>1</sup><br /><span class="text-xs">Version 1.1.0</span>
        </a>
        
      </div>
      <p class="text-gray-400 text-xs mt-2">1) The buttons link you to kdrive from <a href="https://www.infomaniak.com/" target="_blank" class="underline">Infomaniak</a>, a secure and ethical, swiss data storage plattform.</p>
      <a
          href="mailto:be@nedikt.be"
          class="mt-8 text-white px-2 py-1 opacity-70 hover:opacity-100 transition"
        >
          ✉️ Contact Me
        </a>
        <p class="mt-8">With ♥️ build in Fürth, Germany.</p>
    </div>
  </main>
</template>
