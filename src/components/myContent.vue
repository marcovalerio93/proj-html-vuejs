<template>
  <div class="bg-img">
    <div class="container-main">
        <div class="content">
            <i class="fa-solid fa-link-slash"></i>
            <h4>Strength &amp; Condition</h4>
            <img src='../assets/images/divider-x-red.png' alt="x">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Inventore, et.</p>
        </div>
        <div class="content">
            <i class="fa-solid fa-bicycle"></i>
            <h4>Fitness &amp; Cardio</h4>
            <img src='../assets/images/divider-x-red.png' alt="x">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Inventore, et.</p>
        </div>
        <div class="content">
            <i class="fas fa-cloud"></i>
            <h4>Flexability &amp; Rest</h4>
            <img src='../assets/images/divider-x-red.png' alt="x">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Inventore, et.</p>
        </div>
        <div class="content">
            <i class="fa-solid fa-heart-pulse"></i>
            <h4>Health &amp; Diet</h4>
            <img src='../assets/images/divider-x-red.png' alt="x">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Inventore, et.</p>
            
        </div>
        
    </div>
    
  </div>
</template>

<script>
export default {

    name: "MyContent",

}
</script>

<style socped lang="scss">

    div.bg-img{ 
        background-image: url(../assets/images/gym_bkgd_bw-compressor.jpg) ;
        height: 400px;
        background-size: cover;
        background-position: center;

        div.container-main{
            width: 60%;
            margin: auto;
            display: flex;
            justify-content: space-between;
            

            .content{
                text-align: center;
                margin: 80px 10px;

                i{
                    color:#d3615e;
                    border: solid 1px #d3615e;
                    border-radius: 50px;
                    height: 50px;
                    -moz-border-radius:30px;
                    -webkit-border-radius: 30px;
                    width: 50px;
                    padding: 15px;
                    margin-bottom:10px;
                }

                h4{
                    color: #fefefe;
                    margin-bottom: 20px;
                }
                img{
                    margin-bottom: 20px;
                }
                p{
                    color: #aaa9a9;
                }

            }
        }
    }


</style>