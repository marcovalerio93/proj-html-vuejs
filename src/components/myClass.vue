<template>
    <div>
    
        <div class="center">
            <h2> WORLD CLASS Fitness</h2>
            <img src='../assets/images/divider-xx-red.png' alt="">
            <p>At Avada Gym, evrything we do fromtop to bottom is of heghest quality to enurse we're equipped <br> to help you reach your goals of a healty and fit lifestyle.</p>
        </div>
        <div class="bg">
            <div class="conatiner-main">
                <img src="../assets/images/home_img-compressor-400x222.jpg" alt="">
                <div class="input">
                    <h3>Nome</h3>
                    <input class="name" type="text">
                    <h3>Email</h3>
                    <input type="text"> <br>
                    <button class="btn-red">START NOW</button>
                </div>
            
        </div>

        </div>
        
    </div>
    

  
</template>

<script>
export default {
    name: "myClass"

}
</script>

<style scoped lang="scss">
    @import '../styles/generals.scss';
    
    

    div.center{
        text-align: center;
        color: #fefefe;
        padding-top: 100px;
        background-color: #25292b ;
        height: 400px;

        h2{
            padding: 15px;
        }
        img{
            padding: 15px;
        }
        p{
            padding: 15px;
            color: #aaa9a9 ;
        }


    }
    div.bg{
        background-color: #1f2123 ;

        div.conatiner-main{
            width: 50%;
            margin: auto;
            display: flex;
            justify-content: space-between;

            img{
                padding:50px 10px;
            }
            div.input{
                padding: 50px 10px;
                
                h3{
                    color: #fff;
                }
                input{
                    width: 350px;
                }
            }
        }
    }
    
    
</style>