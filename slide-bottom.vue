<script setup lang="ts">
import { computed } from 'vue'
import { useNav, useSlideContext } from '@slidev/client'

const { $page } = useSlideContext()
const nav = useNav()

const current = computed(() => String($page.value).padStart(2, '0'))
const total = computed(() => String(nav.total.value).padStart(2, '0'))
</script>

<template>
  <div class="slide-number-badge" aria-label="Slide number">
    <span>{{ current }}</span>
    <small>/</small>
    <span>{{ total }}</span>
  </div>
</template>

<style scoped>
.slide-number-badge {
  align-items: center;
  background: rgba(255, 255, 255, 0.82);
  border: 1px solid rgba(217, 230, 245, 0.95);
  border-radius: 999px;
  bottom: 18px;
  box-shadow: 0 12px 30px rgba(15, 23, 42, 0.10);
  color: #5c6678;
  display: flex;
  font-size: 10.5px;
  font-weight: 820;
  gap: 5px;
  height: 26px;
  justify-content: center;
  letter-spacing: 0.02em;
  line-height: 1;
  min-width: 58px;
  padding: 0 10px;
  pointer-events: none;
  position: absolute;
  right: 22px;
  z-index: 1000;
}

.slide-number-badge span:first-child {
  color: #1d4ed8;
}

.slide-number-badge small {
  color: rgba(92, 102, 120, 0.52);
  font-size: 10px;
  font-weight: 760;
}
</style>
