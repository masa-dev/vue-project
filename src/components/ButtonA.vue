<template>
    <button type="button">{{ msg }}</button>
</template>

<script>
export default {
    name: 'ButtonA',
    props: {
        msg: String
    }
}
</script>

<style>
    button {
        color: aquamarine;
    }
</style>