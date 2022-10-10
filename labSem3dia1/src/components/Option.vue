<template>
    <h1>New Component on Option</h1>
    <h3>
        {{title}}{{subtitle}}
    </h3>
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
        }
    }
}
</script>
<style></style>