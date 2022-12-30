<template>
    <div>
        <h1>Iteration 4</h1>
    </div>

    <div>
    <ul>
        <li v-for="post in posts">{{ post.title }} {{ post.description }} {{ post.content }}</li>
    </ul>
    </div>

</template>

<script>

export default {
    data(){
        return{
           posts: [
           {
            title: 'El cascabel.',
            description: 'Fantasía.',
            content: 'Mirar hacia el futuro.'
           },
           {
            title: 'Odio o Amor',
            description: 'Sentimientos.',
            content: 'Observarse internamente.'
           },
           {
            title: 'Bailando.',
            description: 'La felicidad.',
            content: 'Todo es posible.'
           }

           ]
        }
    },
    methods:{
    

    }

}
</script>