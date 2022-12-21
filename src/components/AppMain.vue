<script >





</script>

<template>
    <main>
        <section class="wrapper">
            <div class="right-container">
               <div class="info-title">
                <h5>
                    EVERYTHING IN <span> MAXCOACH</span>
                </h5>
                <h1>
                    Learn About our Work Culture at Max Coach
                </h1>
                <p>
                    Spend some time to visit our website or head office and discover our current courses .enrollment procedure, and registration deadline. we're opening new classes every begginning of each month.
                </p>
                <div id="question">
                    Have questions? <a href="#">
                        <strong>
                            Get Free Guide &RightArrow;
                        </strong>
                    </a>
                </div>
               </div>
            </div>
            <div class="left-container">
                <div>
                   <div class="img-container">
                        <img id="full-staff-container" src="../assets/immagini/stock-full-hd-10-ohki1ayywq3cqutettrncduujpoaorifqu4relt2ts.jpg" alt="">
                   </div>
                   <div class="img-container">
                    <img id="about" src="../assets/immagini/about-us-01-ohkia3qg98rq9vg3s0mn2hkflr1migdqdw370qnegc.jpg" alt="" >
                   </div>
                   <div class="img-container">
                    <img id="svg-position" src="../assets/immagini/maxcoach-shape-07-100x100.png" alt="" >
                   </div>
                   <div class="img-container">
                    <img id="svg-position-2" src="../assets/immagini/maxcoach-shape-02.png" alt="" >
                   </div>
                   
                </div>
            </div>
        </section>
    </main>
</template>

<style lang="scss">
    @use"./styles/general.scss" as*;
    @use"./styles/partial/variables.scss" as*;
    .wrapper{
        display: flex;
        width: 80%;
        margin: 100px auto;
        height: 450px;
        .right-container{
            border: 1px solid black;
            margin:0px 10px ;
            width: 45%;
           
        }
         .left-container{
              
                width: 45%;
                margin:0px 10px ;
                position: relative;
                
                #svg-position{
                    position: absolute;
                    left: 74%;
                    bottom: 89%;
                     width: 24%;
                  }
                }
                .img-container{
                    img{
                        max-width: 100%;
                        border-radius: 5px;
                    }
                }
            }
            #full-staff-container{
                position: absolute;
                z-index: 1;
            }
            #about{
                position: absolute;
                bottom: 82%;
                left: 83%;
                width: 32%;
                z-index: 1;
            }
            #svg-position-2 {
                position: absolute;
                z-index: 1;
                top: 63%;
                width: 17%;
                left: 73%;
              }
              .info-title{
                width: 70%;
                margin: auto;
                h5{
                    color: #bbc0c4;
                    span{
                        color: #939699;
                    }
                }
                
              }
              h1{
                font-size: 40px;
                margin: 10px 0px;
            }
</style>
