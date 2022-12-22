<script >





</script>

<template>

        <section class="wrapper">
            <div class="text-container">
                <div class="circle p-circle">

                </div>
               <div class="info-title">
                <h5>
                    EVERYTHING IN <span> MAXCOACH</span>
                </h5>
                <h1 class="titolo">
                    Learn About our <span>Work Culture</span> at Max Coach
                </h1>
                <p>
                    Spend some time to visit our website or head office and discover our current courses .enrollment procedure, and registration deadline. we're opening new classes every begginning of each month.
                </p>
                <div id="domande">
                    Have questions? <a href="#">
                        <strong>
                            Get Free Guide &RightArrow;
                        </strong>
                    </a>
                </div>
               </div>
            </div>
            <div class="poster-container">
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
                   <div class="img-container">
                    <img id="svg-position-3" src="../assets/immagini/maxcoach-shape-08.png" alt="" >
                   </div>
                   
                </div>
            </div>
      </section>
  
   
</template>

<style lang="scss">
    @use"./styles/general.scss" as*;
    @use"./styles/partial/variables.scss" as*;
  
      
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
                top: 97%;
                width: 17%;
                left: 73%;
              }
            
              #svg-position-3 {
                position: absolute;
                top: 67%;
                width: 30%;
               
               
                
                
              }
            
              .info-title{
                width: 70%;
                margin: auto;
            
                p{
                    color: #1fad95;
                    font-size: 13px;
                }
            
                h5{
                    color: #bbc0c4;
                    span{
                        color: #1fad95;
                    }
                }
                
              }
            
            
               
            
            #domande{
                color: #31ad96;
                font-size: 13px;
            
                a{
                    text-decoration: underline;
                    color: #3eaf96;
                }
            }
      
</style>
