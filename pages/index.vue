<template>
    <NuxtLink
        class="underline font-medium pointer"
        :href="firstLesson.path"
    >
        Go to first Lesson
    </NuxtLink>
</template>

<script setup lang="ts">
    const firstLesson = useFirstLesson()
</script>

<style lang="scss" scoped>

</style>