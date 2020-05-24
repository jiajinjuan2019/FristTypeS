<template>
    <div>你好啊{{name}}</div>
</template>
<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
    data () {
        return{
            name:"TypeScript"
        }
    }
})
</script>
