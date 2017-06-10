<template>
    <div class="about">
        <vheader></vheader>
        <h1>{{ msg }}</h1>
        <h2 @click="go('/')">index</h2>
    </div>
</template>
<script>
import vheader from '../components/vheader.vue';


export default {
    name: 'about',
    components : {
        vheader
    },
    data() {
        return {
            msg: 'about page'
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