<template>
    <div>
        <p>
            Para cessar meu github 
            <a v-bind:href="github" target="_blank">        <!-- inserção de links via argumentos diretamente no HTML-->
                Clique aqui
            </a>
        </p>
        <ImagemArgumentos/>
    </div>
</template>

<script>
import ImagemArgumentos from './ImagemArgumentos.vue';

export default{
    name: 'ArgumentosLink',
    components: {
        ImagemArgumentos
    },
    
    data(){
        return{
            github: "https://github.com/MariaClaraRVN"
        }
    }
}
</script>