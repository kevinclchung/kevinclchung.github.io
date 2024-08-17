<script setup lang="ts">

defineProps<{ msg: string }>()

</script>

<template>
    <h1>{{ msg }}</h1>
    <p>
        My name is Kevin Chung, and I'm a frontend developer and UI/UX designer.
    </p>
    <p>
        I'm currently spiffing up my resume at this time. Meanwhile, you can check out
        <a href="https://www.linkedin.com/in/kevinclchung/">my CV on LinkedIn: kevinclchung</a>.
    </p>
</template>

<style scoped>
.read-the-docs {
    color: #888;
}
</style>
