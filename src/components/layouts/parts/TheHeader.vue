<script setup lang="ts">
import HeaderLocale from './HeaderLocale.vue';
import HeaderLogo from './HeaderLogo.vue';
import HeaderPlan from './HeaderPlan.vue';
import HeaderProfile from './HeaderProfile.vue';
</script>

<template>
  <div class="flex items-center h-[var(--height-header)] px-4 lg:px-8 border-b border-soft-200 gap-2 lg:gap-3">
    <HeaderLogo />
    <div class="grow"></div>
    <HeaderPlan />
    <HeaderLocale />
    <HeaderProfile />
  </div>
</template>