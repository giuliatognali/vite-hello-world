<!-- js -->
<script>
export default {
    name: 'AppHero',
    data() {
        return {
            img: "src/assets/confusion-confusion-every.jpg"
        }
    }
}
</script>

<!-- html -->
<template>
    <div> 
        <img :src="img" alt="">
    </div>
</template>

<!-- css -->
<style scoped>
h1 {
    text-decoration: underline;
}
</style>
