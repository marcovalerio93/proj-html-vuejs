<template>
  <div class="bg-ligth ">
     <div class="center ">
          <h2> REAL WORLD RESULTS</h2>
          <img class="divider-xx" src='../assets/images/divider-xx-red.png' alt="">
      </div>
      <div class="grid container-main">
        <div class="post " v-for="(post, index) in posts" :key="index">
          <!-- collegamento img non funzionate 
          <img :src="post.img" alt="review"> -->
          <img src="../assets/images/review_1-compressor.jpg" alt="review">
          <div class="post-r">
            <p class="text">{{post.text}}</p>
            <p class="name">{{post.name}}</p>
            
          </div>
        </div>
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
            img:"../assets/images/review_1-compressor.jpg",           
            text:'Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolore, iste libero. Illo dignissimos nostrum quisquam quibusdam quod necessitatibus, tempora perspiciatis.',
            name:'-Tara Smith'
          },
          { 
            img:'../assets/images/review_2-compressor.jpg',             
            text:'Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellat quo nesciunt dolorum ipsum officiis itaque ad. Beatae illum recusandae nesciunt, quae, aliquid!',
            name:'-Jen Wirth'
          },
          {  
            img:'../assets/images/review_3-compressor.jpg',            
            text:'Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellat quo nesciunt dolorum ipsum officiis itaque ad. Beatae illum recusandae nesciunt, quae, aliquid natus nam corrupti!',
            name:'-Simon Chel'
          },
          {  
            img:'../assets/images/review_4-compressor.jpg',            
            text:'Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellat quo nesciunt dolorum ipsum officiis itaque ad. Beatae illum recusandae nesciunt!',
            name:'-Tara Smith'
          },
        ],
      }
    }
    
}
</script>

<style scoped lang="scss">
  @import '../styles/generals.scss';

  div.grid{
    display: flex;
    flex-wrap: wrap;
    padding-bottom: 100px;

    

    div.post{
      background-color: #1f2123;
      padding: 30px;
      flex-basis: 50%;
      display: flex;
      border: solid 10px #25292b;

      img{
        width: 35%;
        height: auto;
      }

      div.post-r{

        padding:0px 20px;

        p{
        color: #aaa9a9;
        }
        p.text{
          font-style: italic;
          font-weight: 300;

        }
        p.name{
          font-weight: 800;
        }
      }
      
    }
  }

  

</style>