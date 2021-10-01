<template>
    <div class="contaNum">
        <h1>Esse é um contadorzinho besta</h1>
        <p>{{numero}}</p>
        <button @click="contadorUp()" type="button">+</button>
        <button @click="contadorDown()" type="button">-</button>

    </div>    
</template>

<script>
export default ({
    name: 'contaNum',

    data(){
        return {
            numero: 0
        }
    },

    methods:{
        contadorUp(){
            this.numero++;
            },

        contadorDown(){
            this.numero--;
            }
    }
    
})
</script>

<style scoped>

</style>
