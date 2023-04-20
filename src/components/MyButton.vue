<script setup lang="ts">
import type {ButtonProps} from "ant-design-vue";
interface MyButtonProps extends ButtonProps {
    text: string
}

const props = defineProps<MyButtonProps>();
</script>

<template>
    <a-button> {{ props.text }} </a-button>
</template>