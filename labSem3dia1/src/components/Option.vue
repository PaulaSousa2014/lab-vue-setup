<template>
    <h1>New Component on Option</h1>
    <h3>
        {{title}}{{subtitle}}
    </h3>
    <div>
        <button @click="helloWorld">Iteration 3</button>
        <button @click="newFunc"> Change Title</button>
    </div>
</template>
<script>
export default {
    data(){
        return{
            title: 'I am using JavaScript',
            subtitle: ' with Options API'
        }
    },
    methods: {
        newFunc(){
            this.title = 'Changing title with Options API'
        },
        helloWorld(){
            console.log('Hello World')
        }
    }
}
</script>
<style></style>