<template>
    <svg :class="classes" fill="none" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
         viewBox="0 0 24 24" stroke="currentColor">
        <path d="M13 17h8m0 0V9m0 8l-8-8-4 4-6-6"></path>
    </svg>
</template>

<script>
    export default {
        props: ['classes']
    }
</script>