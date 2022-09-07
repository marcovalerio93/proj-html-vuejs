<template>
  <div class="bg-ligth ">
     <div class="center ">
          <h2> REAL WORLD RESULTS</h2>
          <img class="divider-xx" src='../assets/images/divider-xx-red.png' alt="">
      </div>
      <div class="post" v-for="(post, index) in posts" :key="index">
        <p>{{post.text}}</p>
        <p>{{post.name}}</p>
      </div>
      
  </div>
</template>

<script>


export default {
    name: "MyResults",
    data() {
      return{
        posts:[
          { 
            img:'',           
            text:'Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellat quo nesciunt dolorum ipsum officiis itaque ad. Beatae illum recusandae nesciunt, quae, aliquid natus nam corrupti, minus incidunt quas quo ipsa!',
            name:'-Tara Smith'
          },
          { 
            img:'',             
            text:'Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellat quo nesciunt dolorum ipsum officiis itaque ad. Beatae illum recusandae nesciunt, quae, aliquid natus nam corrupti, minus incidunt quas quo ipsa!',
            name:'-Tara Smith'
          },
          {  
            img:'',            
            text:'Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellat quo nesciunt dolorum ipsum officiis itaque ad. Beatae illum recusandae nesciunt, quae, aliquid natus nam corrupti, minus incidunt quas quo ipsa!',
            name:'-Tara Smith'
          },
          {  
            img:'',            
            text:'Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellat quo nesciunt dolorum ipsum officiis itaque ad. Beatae illum recusandae nesciunt, quae, aliquid natus nam corrupti, minus incidunt quas quo ipsa!',
            name:'-Tara Smith'
          },
        ],
      }
    }
    
}
</script>

<style scoped lang="scss">
  @import '../styles/generals.scss';

 



</style>