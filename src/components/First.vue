<template>
<div>
    <h1>Sous direction informatique</h1>
    <h2>{{ msg }}</h2>

    <second text="Salut tous"/>
</div>
</template>





<script>
import Second from './Second'
export default {
    // eslint-disable-next-line vue/multi-word-component-names
    name : 'First',
    components:{
        Second
    },
    props:{
        
        msg:String
    }
    
}
</script>
<style>
h1{
    color: red;
}
</style>