<template>
    <svg :class="classes" fill="none" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
         viewBox="0 0 24 24" stroke="currentColor">
        <path d="M5 13l4 4L19 7"></path>
    </svg>
</template>

<script>
    export default {
        props: ['classes']
    }
</script>