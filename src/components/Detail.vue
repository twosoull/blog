
<template>
    <h5>상세페이지</h5>
    <p>{{블로그글[$route.params.id].title}}</p>
    <p>{{블로그글[$route.params.id].detail}}</p>
    <router-view></router-view>
</template>
   
<script>

export default {
    name : 'Detail',
    props : {
        블로그글 : Array,
    }

}
</script>
   
<style>

</style>
   