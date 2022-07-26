<template>
<Navbar />
<div class="d-flex w-100 bg-warning height">
    <div class="bg-danger w-25 ">
<Sidebar />
</div>
<div class="bg-secondary w-75 ">
<Content />
</div>
</div>
<div>

</div>
</template>
<script>
// import Navbar from './Navbar';
import Navbar from './Navbar.vue';
import Sidebar from './Sidebar.vue';
import Content from './Content.vue';
export default {
    name:"Home",
    components:{
    Navbar,
    Sidebar,
    Content
}
   
}
</script>
<style scoped>
.height{
    height: 90.5vh;
}
</style>