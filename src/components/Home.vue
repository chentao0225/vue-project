<template>
    <div>
        <h2>Home组件</h2>
        <button @click="$emit('click',123)">触发Home组件的自定义事件</button>
    </div>
</template>

<script  type="text/ecmascript-6">
    export default {
        data(){
            return {
               
            }
        },
        
    };
</script>

<style lang="stylus" rel="stylesheet/stylus" scoped>
    
 
</style>
