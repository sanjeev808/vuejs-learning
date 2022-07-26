<template>
    <h1> this is condition rendering page</h1>

    <h3 v-if="show">condition rendering of vue js </h3>
    <h3 v-else>condition rendering else block </h3>
    <button v-on:click="display" >Toggle button</button>

</template>
<script>
export default {
    name: 'ConditionRendering',
    props:{
        data:String,
    },data()
    {
        return { show:false}
    },
    methods:{
        display()
        {
           this.show = !(this.show)
        }

    }
}
</script>