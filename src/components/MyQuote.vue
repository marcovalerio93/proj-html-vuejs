<template>
  <div class="bg-img">
    <div class="container-tex center quotes" v-for="(quote, index) in quotes" :key="index">
        <p class="quote">{{quote.text}}</p>
        <p class="autor">{{quote.autor}}</p>


    </div>


  </div>
</template>

<script>
export default {
    name: "MyQuote",
    data(){
        return{
            quotes:[
                {
                    text: '"I fear not the man who has practiced 10,000 kicks once, but I fear the man who has practiced one kick 10,000 times."',
                    autor: 'BRUCE LEEE - QUOTE OF THE DAY'
                }
            ]

        }
    }

}
</script>

<style scoped lang="scss">

    @import '../styles/generals.scss';

    div.bg-img{ 
        background-image: url(../assets/images/home-testimonial-bg.jpg) ;
        min-height: 500px;
        background-size: cover;
        background-position: center;

        div.container-tex{
            width: 40%;
            margin:auto
        }
        p{
            color: #fefefe;
        }
        p.quote{
            font-size: 30px;
            margin: 40px 0px;
        }
        p.autor{
            font-weight: 700;
        }
    }





</style>