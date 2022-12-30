<template>
    <div>
        <h1>Iteration 3</h1>
        <h1 v-if="isAwesome">Vue is awesome!</h1>
        
    </div>

</template>

<script>

export default {
    data(){
        return{
           isAwesome: true
        }
    },
    methods:{
    

    }

}
</script>