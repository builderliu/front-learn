<template>
    <div>
        <h1>{{ name }}</h1>
        <h2>{{ addr }}</h2>
        <br>
    </div>

</template>


<script>
export default {
    name:School,
    data() {
        return {
            name: 'shsangguigu',
            addr: 'beijing'
        }
    },
    methods: {

    }
}

</script>


<style scoped>
.demo {
    background-color: beige;
}
</style>