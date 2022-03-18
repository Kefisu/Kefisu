<template>
  <div class="fixed bottom-10 right-0">
    <div id="social-bar" class="flex">
      <a class="p-4 text-slate-400 hover:text-cyan-400 transition hover:-translate-y-1 hover:translate-x-1" href="https://github.com/Kevin-Jansen" target="_blank">
        <svg class="h-6 w-6" fill="none" stroke="currentColor" stroke-linecap="round"
             stroke-linejoin="round"
             stroke-width="2" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
          <path
              d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"/>
        </svg>
      </a>
      <a class="p-4 text-slate-400 hover:text-cyan-400 transition hover:-translate-y-1 hover:translate-x-1" href="https://www.linkedin.com/in/kevin-jansen-0ba19988/"
         target="_blank">
        <svg class="h-6 w-6" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round"
             stroke-width="2" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
          <path d="M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-2-2 2 2 0 0 0-2 2v7h-4v-7a6 6 0 0 1 6-6zM2 9h4v12H2z"/>
          <circle cx="4" cy="4" r="2"/>
        </svg>
      </a>
      <a class="p-4 text-slate-400 hover:text-cyan-400 transition hover:-translate-y-1 hover:translate-x-1" href="https://www.instagram.com/kevin_jansen_official/"
         target="_blank">
        <svg class="h-6 w-6" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round"
             stroke-width="2" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
          <rect height="20" rx="5" ry="5" width="20" x="2" y="2"/>
          <path d="M16 11.37A4 4 0 1 1 12.63 8 4 4 0 0 1 16 11.37zM17.5 6.5h.01"/>
        </svg>
      </a>
    </div>
  </div>
</template>

<script>
export default {
  name: "SocialBar"
}
</script>

<style scoped>
#social-bar:after {
  content: "";
  display: block;
  width: 80px;
  height: 1px;
  background-color: rgb(148 163 184/1);
  margin: auto 0;
}
</style>
