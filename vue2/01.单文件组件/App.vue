<template>
    <div>
        <School>
            <Student></Student>
        </School>
    </div>
  
</template>

<script>
import School from './School.vue'
import Student from './Student.vue'
export default {
    name:'app',
    components: { School, Student }, //注册组件
 
}






</script>

<style>

</style>