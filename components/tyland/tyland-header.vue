<script setup>
</script>

<template>
  <header class="flex w-full justify-center px-8 xl:px-0">
    <nav class="flex w-full max-w-7xl items-center justify-between py-2">
      <div>
        <a aria-label="伺服器監控系統" href="/">
          <div class="flex items-center justify-between">
            <div class="mr-3">
              <Icon class="h-12 w-12" name="logos:nuxt-icon" />
            </div>
            <div class="hidden h-6 text-2xl font-semibold text-gray-700 sm:block hover:text-emerald-500">
              伺服器監控系統
            </div>
          </div>
        </a>
      </div>
      <div class="flex items-center text-base leading-5">
        <div class="flex flex-row items-center">
          <NuxtLink
            class="px-3 py-2 text-gray-700 transition hover:text-emerald-500"
            to="/login"
          >
            登入
          </NuxtLink>
        </div>
      </div>
    </nav>
  </header>
</template>
