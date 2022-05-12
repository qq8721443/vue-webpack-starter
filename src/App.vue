<template>
    <h1>{{ msg }}</h1>
    <button @click="msg += '!'">Click!</button>
    <Button></Button>
</template>
<script>
import Button from '~/components/Button';

export default {
    components: {
        Button
    },
    data() {
        return {
            msg: 'Hello Vue!'
        }
    }
}
</script>
<style lang="scss">
$color: red;
h1 {
    color: $color;
}
</style>
