<template>
    <component :is="tag">
        <slot></slot>
    </component>
</template>

<script setup>

const props = withDefaults(defineProps({
    tag: {
        type: String,
        default: 'div'
    }
}))
</script>
