<template>
  <div style="margin: 10px;">
    Main Inside page index
    {{ $attrs.data }}
  </div>
</template>

<script setup>
const attrs = useAttrs()
console.warn('attr', attrs.data)
</script>

