<template>
  <div>
    <div class="bg-ligth ">
     <div class="center ">
          <h2>HIGH PERFORMANCE FACILITES</h2>
          <img class="divider-xx" src='../assets/images/divider-xx-red.png' alt="">
      </div>
      <div class="grid-3 container-main">
        <img src='../assets/images/home-image1-200x135.jpg' alt="facilities"/>
        <img src='../assets/images/home-image2-200x135.jpg' alt="facilities"/>
        <img src='../assets/images/home-image3-200x135.jpg' alt="facilities"/>
        <img src='../assets/images/home-image4-200x135.jpg' alt="facilities"/>
        <img src='../assets/images/home-image54-200x135.jpg' alt="facilities"/>
        <img src='../assets/images/home-image6-200x135.jpg' alt="facilities"/>
       
      </div>
    </div>


  </div>
</template>

<script>
export default {
    name: "MyPerformance"

}
</script>

<style scoped lang="scss">
    @import '../styles/generals.scss';

    div.grid-3{
        display: flex;
        flex-wrap: wrap;
        padding-bottom: 100px;
        
        img{
            flex-basis: 33%;
            padding: 20px;
        &:hover{
            transform: scale(1.1);
        }
        }
    }

</style>