<!-- js -->
<script>
export default {
    name: 'AppTitle',
    data() {
        return {
            message: 'La mia prima app con Vite! '
        }
    }
}
</script>

<!-- html -->
<template>
    <h1>{{ message }}</h1>
</template>

<!-- css -->
<style scoped>
h1 {
    color: lightgray;
}
</style>
