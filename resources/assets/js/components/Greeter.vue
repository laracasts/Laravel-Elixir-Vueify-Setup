<template>
    <div>
        <h1>Hello, {{ name }}!</h1>

        <input type="text" v-model="name">
    </div>
</template>

<script>
    export default {
        data() {
            return {
                name: 'Laracasts'
            };
        }
    };
</script>

<style>
    h1 {
        color: red;
    }
</style>