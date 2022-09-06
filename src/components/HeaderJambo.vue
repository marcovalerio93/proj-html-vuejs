<template>
  <div>
    <header>
        <div class="container">
            <nav>
                <img src='../assets/images/gym_logo_1x.png' alt="">
            
                <ul>
                    <li v-for="(link, index) in links" :key="index">
                        <a :href="link.url">{{link.text}}</a>
                    </li>
                    
                </ul>
            </nav>
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
header{
    
    height: 3000px;
    background-image: url('../assets/images/home-banner.jpg');
    background-repeat:no-repeat ;
    background-size: contain ;
    
    .container{
        width: 90%;
        margin: auto;
        padding-top: 20px;
        
        nav{
            display: flex;
            justify-content: space-between;

            ul{
                list-style: none;

                li{
                    display: inline-block;
                    margin: 0px 10px;
                    
                    a{
                        text-decoration: none;
                        color: #fefefe ;
                        
                    }
                }
            }

        }
    }
}

</style>