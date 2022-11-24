<template>
    <div>
        <h3>学校名称：{{name}}</h3>
        <h3>学校地址：{{address}}</h3>
        <member></member>
    </div>
</template>

<script>
export default {
    data() {
        return {
            name: '黑猫堂',
            address: "Tokoy"
        }
    },
    components:{
        member
    }

}
</script>

<style>

</style>