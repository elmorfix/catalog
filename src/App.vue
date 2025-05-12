<template>
  <div class="bg-slate-200 w-full h-[100dvh]">
    <nav class="bg-white/90 p-4 sticky top-0">
      <RouterLink to="/">Home</RouterLink>
    </nav>
    <main class="p-5">
      <RouterView />
    </main>
  </div>
</template>
