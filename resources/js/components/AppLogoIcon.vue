<script setup lang="ts">
import type { HTMLAttributes } from 'vue';

defineOptions({
    inheritAttrs: false,
});

interface Props {
    className?: HTMLAttributes['class'];
}

defineProps<Props>();
</script>

<template>
    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 50 32" width="300" height="300" fill="black">
        <rect x="0" y="0" width="64" height="32" rx="6" ry="6" />
        <text x="50%" y="50%" dominant-baseline="middle" text-anchor="middle"
              font-size="18" font-weight="800" font-family="Arial, sans-serif"
              fill="white">
            T-tix
        </text>
    </svg>
</template>



