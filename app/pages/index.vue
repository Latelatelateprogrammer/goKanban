<script setup lang="ts">
import { page } from '#build/ui';

</script>

<template>
  <UApp>
    <page />
    <UButton>
      <template #icon>
        <UIcon name="mdi:home" />
      </template>
      Home
    </UButton>
  </UApp>
</template>
