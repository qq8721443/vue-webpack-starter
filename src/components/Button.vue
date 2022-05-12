<template>
    <button @click="log">여기 바꾸면~!</button>
</template>
<script>
export default {
    methods: {
        log() {
            console.log('야호~');
        }
    }
}
</script>