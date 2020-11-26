<template>
    <div class="container">
        <div class="row">
            <appQuote>{{ quote }}</appQuote>
        </div>
    </div>
</template>

<script>

    import Quote from './Quote.vue';

    export default{ 
        props:['quotes'],
        components:{
            appQuote:Quote
        }
    }
</script>

<style>

</style>>