<template>
    <div>
        Esta es una alerta.
    </div>
</template>

<script setup>
  const props = defineProps({
    alerta: {
        type: Object,
        required: true
    }
  });
</script>