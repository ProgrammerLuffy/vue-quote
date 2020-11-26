<template>
    <div class="container">
        <appQuoteGrid :quotes="quotes"></appQuoteGrid>
    </div>
</template>

<script>
    import QuoteGrid from './component/QuoteGrid.vue';
    export default {
        data(){
            return{
                maxQuote:10,
                quotes:['Just a Quote'],
            }
        },
            components:{
                'appQuoteGrid':QuoteGrid
            }
    }
</script>

<style>
</style>
