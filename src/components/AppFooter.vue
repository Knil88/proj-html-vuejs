<script >
export default{
    data() {
        return {
            imgSocial: [
                {
                    img: 'img/footer-facebook.png',
                    link: '#'
                }, {
                    img: 'img/footer-twitter.png',
                    link: '#'
                }, {
                    img: "img/footer-youtube.png",
                    link: '#'
                }, {
                    img: "img/footer-pinterest.png",
                    link: '#'
                }, {
                    img: "img/footer-periscope.png",
                    link: '#'
                }],
            footerElement: [
                {
                    title: 'Address',
                    listLink: [
                        {
                            text: '382 NE 191st # 87394 Miami,FL 33179-3899',
                            url: '#',
                            
                        },
                        {
                            text: '+1(305)547-9909(9am-5pmEST,Monday_Friday)',
                            url: '#',
                            
                        },
                        {
                            text: 'support@maxcoach.com',
                            url: '#',
                            
                        },
                       
                       
                    ]
                },
                
            ],
            footerElement2: [
                {
                    title: 'Explore',
                    listLink: [
                        {
                            text: 'Start here',
                            url: '#',
                            
                        },
                        {
                            text: 'Blog',
                            url: '#',
                            
                        },
                        {
                            text: 'About us',
                            url: '#',
                            
                        },
                       
                       
                    ]
                },
                {
                    title: '',
                    listLink: [
                        {
                            text: '',
                            url: '',
                            
                        },
                        {
                            text: 'Success story',
                            url: '#',
                            
                        },
                        {
                            text: 'Courses',
                            url: '#',
                            
                        },
                        {
                            text: 'Contact us',
                            url: '#',
                            
                        },
                       
                       
                    ]
                },
                {
                    title: 'Information',
                    listLink: [
                        {
                            text: 'Memebership',
                            url: '#',
                            
                        },
                        {
                            text: 'Purchase guide',
                            url: '#',
                            
                        },
                        {
                            text: 'Privacy policy',
                            url: '#',
                            
                        },
                        {
                            text: 'Terms of Service',
                            url: '#',
                            
                        },
                       
                       
                    ]
                },
                
            ],
        }
    },
}




</script>
    
<template>
    <footer>
        <div class="flex-footer">
          <div>
            <ul v-for= "(element, index) in footerElement">
                <li class="titolo-li">
                  {{element.title}}
                </li>
                <li v-for="link in element.listLink" class="">
                  <a :href="link.url">
                      {{ link.text }}
                  </a>
              </li>
              </ul>
          </div>
        
        <div class="flex">

            <ul v-for= "(element, index) in footerElement2">
                <li class="titolo-li">
                  {{element.title}}
                </li>
                <li v-for="link in element.listLink" class="li-p">
                  <a :href="link.url">
                      {{ link.text }}
                  </a>
              </li>
              </ul>
        </div>
        </div>
        <div id="icon-container">
                <a  v-for="img in imgSocial"  :href="img.link">
                <img :src="img.img" alt="">
            </a>
          </div>
          <div id="upArrow">
            <a href="#">
                &UpArrow;
            </a>
          </div>
          <div id="footer-copyright" >
            &#169; MaxCoach.All Rights Reserved
          </div>
         
    </footer>
</template>

<style lang="scss">
    @use"./styles/general.scss" as*;
    @use"./styles/partial/variables.scss" as*;
    footer{
        background-color: #171621;
        color: #aba290;
        position: relative;
        
    }
    .flex-footer{
        display: flex;
        justify-content: space-around;
        width: 80%;
        margin: auto;
        padding-top: 20px;
        padding-bottom: 5px;
        h4{
            color: #fff;
            
        }
        .flex{
            display: flex;
        }
        a{
            color: #ababab;
        }
        .titolo-li{
            color:#ffffff;
            margin-left: 15px;
        }
    }
    #icon-container{
        
            margin: 0px 14%;
            img{
                width:3%
            }
    }
    #footer-copyright{
        text-align: center;
    }

    #upArrow{
        background-color: #20ad96;
        
        padding: 5px 0px;
        border-radius: 50%;
        position: absolute;
        bottom: 3%;
        left: 96%;
        a{
            color: white;
        }
    }
    
</style>
