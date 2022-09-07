<template>
  <div>
    <div class="post conatiner-main">
        <p>{{post.text}}</p>
        <p>{{post.name}}</p>
    </div>

  </div>
</template>

<script>
export default {
    name: "MyPost",
    data() {
      return{
        posts:[
          {            
            text:'Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellat quo nesciunt dolorum ipsum officiis itaque ad. Beatae illum recusandae nesciunt, quae, aliquid natus nam corrupti, minus incidunt quas quo ipsa!',
            name:'-Tara Smith'
          },
          {            
            text:'Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellat quo nesciunt dolorum ipsum officiis itaque ad. Beatae illum recusandae nesciunt, quae, aliquid natus nam corrupti, minus incidunt quas quo ipsa!',
            name:'-Tara Smith'
          },
          {            
            text:'Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellat quo nesciunt dolorum ipsum officiis itaque ad. Beatae illum recusandae nesciunt, quae, aliquid natus nam corrupti, minus incidunt quas quo ipsa!',
            name:'-Tara Smith'
          },
        ]
      }
    }


}
</script>

<style scoped lang="scss">
    @import '../styles/generals.scss';
    p{
        color: #fff;
    }
    

</style>