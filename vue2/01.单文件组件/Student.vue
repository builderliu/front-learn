<template>
    <div>
        <h1>{{ name }}</h1>
        <h2>{{ sex }}</h2>
        <br>
    </div>

</template>


<script>
export default {
    name:Student,
    data() {
        return { 
            name: 'shsangguigu',
            sex: 'male'
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