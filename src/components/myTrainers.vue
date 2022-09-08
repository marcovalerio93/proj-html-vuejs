<template>
  <div>
    <div class="bg-dark">
        <div class="center">
          <h2>MET OUR TRAINER</h2>
          <img class="divider-xx" src='../assets/images/divider-xx-red.png' alt="">
        </div>
        <div class="container-main">
            <div class="grid-3 ">
                <div class="card"  v-for="(card, index) in cards" :key="index">
                    <img src="../assets/images/trainer1.jpg" alt="">
                    <p class="name">{{card.name}} <br>{{card.role}}</p>
                    <p class="text">{{card.text}}</p>
                    <p class="icons"></p>
                </div>               
            </div>
            <div class="center">
                <button class="btn"> SEE ALL TRAINERS</button>
            </div>    
        </div>

    </div>

  </div>
</template>

<script>
export default {
    name: "MyTrainers", 
    data(){
        return{
            cards:[
                {
                    img:'../assets/images/trainer1.jpg',
                    name:'Anna Baker',
                    role:'Personal Trainer',
                    text:'Lorem ipsum dolor, sit amet consectetur adipisicing elit. Earum molestias optio recusandae!'
                },
                {
                    img:'../assets/images/trainer3.jpg',
                    name:'Anna Warren',
                    role:'Personal Trainer',
                    text:'Lorem ipsum dolor, sit amet consectetur adipisicing elit. Earum molestias optio recusandae!'
                },
                {
                    img:'../assets/images/trainer4.jpg',
                    name:'Peter rice',
                    role:'Personal Trainer',
                    text:'Lorem ipsum dolor, sit amet consectetur adipisicing elit. Earum molestias optio recusandae!'
                }

            ]
        }
    }

}
</script>

<style scoped lang="scss">
    @import '../styles/generals.scss';
    @import '../styles/grid.scss';

    div.card{
        background-color:#25292b ;
        flex-basis: 33%;
        border: solid 10px #1f2123;

        img{
            width: 100%;
            height: auto;
        &:hover{
            transform: scale(1.1);
        }
        }
        p{
            padding: 15px;
            color: #fefefe;
        }
        p.name{
            font-weight: 800;
        }
        p.text{
            color:#aaa9a9;
        }

    }

</style>