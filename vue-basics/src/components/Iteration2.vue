<template>
    <div>
        <h1>Iteration 2</h1>
        <h2>{{ 2 + 2 }}</h2>
        <h2>{{ textFunction() }}</h2>
    </div>

</template>

<script>

export default {
    data(){
        return{
           
        }
    },
    methods:{
        textFunction(){
            return "Iteración 2!"

        }

    }


}
</script>