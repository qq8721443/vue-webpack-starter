<template>
    <header>
        <RouterLink to="/">Home..</RouterLink>
        <RouterLink to="/about">About..</RouterLink>
    </header>
    <section>
        <RouterView></RouterView>
    </section>
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
    },
}
</script>
<style lang="scss" scoped>
header {
    background-color: #fff;
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 80px;
    display: flex;
    align-items: center;
}
section {
    margin-top: 80px;
}
</style>
