<template>
<div>
<h1> this is hello page</h1>
<!-- <h2>{{data}}</h2> -->
<!-- <button v-on:click="hello" >call Hello Functio</button> -->
<button v-on:click="hello('hello call')" >call Hello Functio</button>
</div>
</template>
<script>
export default {
    name:"Home",
    props:{
        data : String
    },
    methods:{
        hello(data)
        {
            alert(data)
            // alert("this is hello function button")
        }
    }
}
</script>
