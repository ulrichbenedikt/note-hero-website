<script setup>
import {mac, windows} from './downloads.json'
</script>

<template>
  
  <main class="min-h-screen bg-black text-white">
    <img src="/background.png" alt="Note Hero Logo" class="object-cover h-screen w-full absolute opacity-15"/>
    <div class="relative flex flex-col items-center justify-center px-4 py-12 min-h-screen">
      <img src="/logo.png" alt="Note Hero Logo" class="w-32 h-32 mb-6" />
      <h1 class="text-4xl font-bold mb-4">Note Hero</h1>
      <p class="text-lg text-center max-w-md mb-8">
        A minimalist note app for focused thinking. <br />Markdown, client linking, shortcuts, and more. 
      </p>
      <div class="flex flex-col gap-4 sm:flex-row ">
        <a
          :href="mac.link"
          download
          style="background: linear-gradient(235deg,rgba(253, 29, 29, 1) 0%, rgba(252, 69, 203, 1) 100%);"
          class="bg-white text-white px-6 py-3 rounded-xl opacity-80 hover:opacity-100 transition"
        >
          Download for macOS<sup>1</sup><br /><span class="text-xs">Version {{mac.version}}</span>
        </a>
        <a
          :href="windows.link"
          target="_blank"
          download
          style="background: linear-gradient(203deg,rgba(230, 23, 23, 1) 0%, rgba(245, 108, 208, 1) 100%);"
          class="text-white px-6 py-3 rounded-xl opacity-80 hover:opacity-100  transition"
        >
          Download for Windows<sup>1</sup><br /><span class="text-xs">Version {{windows.version}}</span>
        </a>
        
      </div>
      <p class="text-gray-400 text-xs mt-2">1) These buttons take you to kDrive by <a href="https://www.infomaniak.com/" target="_blank" class="underline">Infomaniak</a> — a secure, privacy-focused cloud storage service based in Switzerland and fully compliant with European data protection laws.</p>
      <a href="https://note-hero-app.nedikt.be"
          style="background: linear-gradient(255deg,rgba(253, 29, 29, 1) 0%, rgba(252, 69, 203, 1) 100%);"
          class="bg-white text-white mt-3 px-6 py-3 rounded-xl opacity-80 hover:opacity-100 transition">-> Or start now and use it online!</a>
      
        <p class="mt-14">With ♥️ build in ☘️Fürth, Germany.</p>
        <a
          href="mailto:be@nedikt.be"
          class="text-white px-2 py-1 opacity-70 hover:opacity-100 transition"
        >
          ✉️ Contact Me
        </a>
    </div>
  </main>
</template>
