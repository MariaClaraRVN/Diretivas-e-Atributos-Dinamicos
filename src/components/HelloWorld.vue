<template>
  <div>
    <p v-if="esta_trabalhando">     <!-- Se esta_trabalhando for verdadeira, irá mostrar a frase -->
      Maria Clara RVN
    </p>

    <p v-else>                       <!-- Se não, irá mostrar outra frase, lembrar que o elese só vai embaixo de if -->
      Maria Clara Rezende Vianna
    </p>

    <ul>
      <li>Js</li>
      <li>HTML</li>
      <li>CSS</li>
    </ul>

    <p v-if="5<3">Oláááá</p>        <!-- Se esta_trabalhando for verdadeira, irá mostrar a frase -->
    <p v-else>Oiiii</p>           <!-- Se não, irá mostrar outra frase, lembrar que o elese só vai embaixo de if -->

    <p v-show="mostra">           <!-- Se mostra for verdadeiro, irá mostrar o conteudo, caso contrário, nã. -->
      Lorem ipsum dolor, sit amet consectetur adipisicing elit. Voluptatibus incidunt corrupti rerum rem nam dolores placeat dolor, non, est ratione temporibus natus similique nesciunt cumque nostrum dolorem fugiat veniam libero?
    </p>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data(){
    return{
      esta_trabalhando: true ,
      mostra: true
    }
  }
}
</script>

