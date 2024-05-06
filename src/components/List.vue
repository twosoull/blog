
<template>
    <div v-for="(글,i) in 블로그글" key=i>
        <h5 @click="$router.pust('/detail/0')">{{ 글.title }}</h5>
        <p>{{ 글.date }}</p>
    </div>

 </template>
    
<script>

export default {
    name : 'List',
    props : {
        블로그글 : Array
    },
    
}
</script>
    
<style>

</style>
    