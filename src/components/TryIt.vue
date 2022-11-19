<template>
    <div>{{ msg }}</div>
    <div v-html = "ChangeHtmlTag"></div>
</template>
<script>
    export default{
        name: 'TryIt'  ,
        props :{
            msg : String ,
            ChangeHtmlTag : String
            }
        }
</script>