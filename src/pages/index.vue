<template>
    <div class="index">
        <img src="../assets/logo.png">
        <h1>{{ msg }}</h1>
        <h2 @click="go('about')">about</h2>
    </div>
</template>
<script>
export default {
    name: 'index',
    data() {
        return {
            msg: 'index page'
        }
    },
    methods: {
        go(route) {
            this.$router.push(route)
        }
    }
}
</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>