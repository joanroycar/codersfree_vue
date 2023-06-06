<template>

    <h1>PERU CAMPEAON</h1>
    <button v-on:click="disminuir()">-</button>
    {{ contador }}
    <button v-on:click="aumentar()">+</button>
    
</template>


<script>


export default {

    data(){
        return {
            contador:0
        }
    },
    methods:{
        disminuir(){

            this.contador--
            
        },
        aumentar(){
            this.contador++


        }
    }
    // components:{
    //     Counter
    // }
    
}


</script>

<style scoped>
h1{
    color: red;
}
</style>