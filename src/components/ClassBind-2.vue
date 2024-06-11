<template>
    <p v-bind:style ="{backgroundColor: '#ccc', color: c}" >El mensaje se ha enviado satisfactoriamente!</p>
    <button @click="handelClick">Cambiar color</button>
</template>

// Lindeo de clases
<script lang="ts" >
    import { defineComponent, ref} from 'vue';
    export default defineComponent({
        name : 'ClassBind',
        setup(){
            let c = ref('#fff')
            const handelClick = () => {c.value = '#ff0000'}
            return {c, handelClick}
        }
    })
</script>

<style>

</style>