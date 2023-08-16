<template>
  <div>
    <VipLayoutHeader />
    <slot />
    <VipLayoutFooter />
  </div>
</template>

<script setup lang="ts">
import VipLayoutHeader from '../components/VipLayoutHeader.vue'
import VipLayoutFooter from '../components/VipLayoutFooter.vue'
</script>
