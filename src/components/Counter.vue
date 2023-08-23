<template>
    <div>{{ count }}</div>
    <button @click="add">add</button>
</template>

<script>
export default {
    name: 'DemoSsrFrameworksCounter',

    data() {
        return {
            count: 0
        };
    },

    mounted() {
        
    },

    methods: {
        add(){
            this.count ++
        }
    },
};
</script>

<style lang="less" scoped>

</style>