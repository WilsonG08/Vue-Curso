<template>
    <ul>
        <li v-for = "country in countries" :key="country.code">{{ country.name }}</li>
    </ul>
</template>

<script lang="ts" setup>
    import {Ref, ref} from 'vue'
    //let countries:Ref<Array<string>> = ref([
        //'Spain', 'France', 'UK', 'Italy', 'Portugal'
    //])
    interface ICountry{
        code: string,
        name: string
    }
    let countries:Ref<Array<ICountry>> = ref([
        {
            code : 'es',
            name : 'Spain'
        },
        {
            code : "en",
            name : "UK"
        },
        {
            code : "fr",
            name : "Francia"
        },
        {
            code : "it",
            name : "Italy"
        },
        {
            code : "pt",
            name : "Portugal"
        }
    ])
</script>

<style>
</style>