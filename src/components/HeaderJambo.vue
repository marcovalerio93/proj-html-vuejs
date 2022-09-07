<template>
  <div>
    <header>
        <div class="container">
            <nav>
                <img src='../assets/images/gym_logo_1x.png' alt="Gim logo">
            
                <ul>
                    <li v-for="(link, index) in links" :key="index">
                        <a :href="link.url" :class="link.active?'active':''">{{link.text}}</a>
                    </li>   
                </ul>
            </nav>
            <div class="center">
                <h1>NO PAIN NO GAIN</h1>
                <p>Motivation in wath gets you started. Habitis what keeps you going.</p>
                <button class="btn">JOIN US TODAY</button>

            </div>
        </div>
    </header>

  </div>
</template>

<script>
export default {
     name: "HeaderJambo",
     data() {
        return{
            links:[
                {
                    text:'HOME',
                    url:'#',
                    active: true                    
                },
                {
                    text:'ABOUT US',
                    url:'#',
                    active: false                   
                },
                {
                    text:'FACILITIES',
                    url:'#',
                    active: false                   
                },
                {
                    text:'MEBERSHIP',
                    url:'#',
                    active: false                   
                },
                {
                    text:'TESIMONIAL',
                    url:'#',
                    active: false                   
                },
                {
                    text:'BLOG',
                    url:'#',
                    active: false                   
                },

            ]
        }
     }


}
</script>

<style lang="scss">

    @import '../styles/generals.scss';

    header{
        height: 860px;
        background-image: url('../assets/images/home-banner.jpg');
        background-repeat:no-repeat ;
        background-size: contain;
        background-color: #25292b;
        
        
        .container{
            width: 90%;
            margin: auto;
            padding-top: 20px;
            
            nav{
                display: flex;
                justify-content: space-between;

                ul{
                    list-style: none;
                    margin-top: 50px;

                    li{
                        
                        display: inline-block;
                        margin: 0px 10px;
                        
                        a{
                            text-decoration: none;
                            color: #fefefe ;
                        &.active, &:hover{
                            color: #d3615e;
                        }
                            
                        }
                    }
                }

            }
            div.center{
                text-align: center;
                color: #fefefe;
                margin-top: 180px;

                h1{
                    font-size: 100px;
                    margin-bottom: 20px;
                }
                p{
                    margin-bottom: 30px;
                }
                .btn{
                    padding: 10px 20px;
                    border: solid 1px #aeafae;
                    background: none;
                    color: #aeafae;
                    font-size: 10px;
                &:hover{
                        border:solid 1px #d3615e;
                        color: #d3615e;
                        font-size: 15px;
                        }
                }
            }
        }
    }

</style>