<template>
    <div>
        <img :src="avatar" :alt="descricao">        <!-- inserção de imagens via argumentos diretamente no HTML de forma resumida-->
    </div>
</template>

<script>
export default{
    name: 'ImagemArgumentos' ,
    data(){
        return{
            avatar: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQiO8hED-plK60tGTWCI2diFZ1R3G1DiiRKAj4W-fyT657qX7-5DQ880VOR1EEHUJXBzVI&usqp=CAU" ,
            descricao: "Imagem do React vs Vue"
        }
    }
}
</script>