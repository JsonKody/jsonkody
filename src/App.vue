<script setup lang="ts">
// const jk = `<img src="/images/jk.svg" class="rounded-full">`;
const bekinka = `<img src="/images/bekinka.avif" class="rounded-full">`;
const num = `<img src="/images/num.avif" class="rounded-full">`;
const toolpop = `<img src="/images/toolpop.avif" class="rounded-full">`;
const snejk = `<img src="/images/snejk.avif" class="rounded-full">`;
const github = `<img src="/images/github.avif" class="rounded-full">`;
const discord = `<img src="/images/discord.avif" class="rounded-full">`;
const twitch = `<img src="/images/twitch.avif" class="rounded-full">`;
const youtube = `<img src="/images/jk.avif" width="120" height="120" class="rounded-full">`;
</script>

<template>
  <div class="">
    <h1
      v-pop:bottom="'YouTube'"
      class="p-4 trans text-7xl roboto-mono text-transparent bg-clip-text hover:brightness-150 bg-gradient-to-r from-25% from-purple-700 to-teal-200"
    >
      <a href="https://www.youtube.com/jsonkody"> {jk} </a>
    </h1>

    <div class="w-full absolute top-0 right-0 flex justify-center">
      <div class="main-links-wrap">
        <a
          class="main-link text-purple-400 hover:text-pink-300"
          href="https://bekinka.cz"
          target="_blank"
          v-pop.html="bekinka"
        >
          bekinka.cz
        </a>
        <a
          class="main-link text-emerald-300 hover:text-green-100"
          href="https://num.jsonkody.cz"
          target="_blank"
          v-pop.html="num"
        >
          num
        </a> 
        <a
          class="main-link text-pink-500 hover:text-pink-300"
          href="https://snejk.bekinka.cz"
          target="_blank"
          v-pop.html="snejk"
        >
          snejk
        </a>
        <a
          class="main-link text-white hover:text-blue-300"
          href="https://www.npmjs.com/package/toolpop"
          target="_blank"
          v-pop.html="toolpop"
        >
          toolpop
        </a>
        <a
          class="main-link text-gray-400 hover:text-gray-100"
          href="https://github.com/jsonkody"
          target="_blank"
          v-pop.html="github"
        >
          github
        </a>
        <a
          class="main-link text-blue-400 hover:text-pink-300"
          href="https://discord.gg/djVwV5FT"
          target="_blank"
          v-pop.html="discord"
        >
          discord
        </a>
        <a
          class="main-link text-purple-400 hover:text-pink-300"
          href="https://www.twitch.tv/jsonkody"
          target="_blank"
          v-pop.html="twitch"
        >
          twitch
        </a>
        <a
          class="main-link text-red-400 hover:text-pink-300"
          href="https://www.youtube.com/jsonkody"
          target="_blank"
          v-pop.html="youtube"
        >
          youtube
        </a>
      </div>
    </div>
  </div>
</template>

<style scoped></style>
