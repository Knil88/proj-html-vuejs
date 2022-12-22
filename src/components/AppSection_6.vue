<script >





</script>

<template>

    <section class="wrapper white">
    
        <div class="poster-container">
            <div class="img-container" id="shape_1">
                <img src="../assets/immagini/maxcoach-shape-01.png" alt="">
              </div>
              <div class="img-container" id="shape_2">
                <img src="../assets/immagini/maxcoach-shape-05.png" alt="">
              </div>
              <div class="img-container">
                <img  id="shape_3" src="../assets/immagini/maxcoach-shape-07.png" alt="">
              </div>
            <div class="img-container" id="cloud-1">
                <img src="../assets/svg-0.svg" alt="">
              </div>
          <div class="img-container" id="svg-5-p">
            <img src="../assets/immagini/home-3-team-image.png" alt="">
          </div>
        </div>
        <div class="text-container">
            <div class="circle-4 p-circle-4">

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
                Have questions? <a href="#" id="link-domande">
                    <strong>
                        Get Free Guide &RightArrow;
                    </strong>
                </a>
            </div>
           </div>
        </div>
  </section>


</template>

<style lang="scss">
    @use"./styles/general.scss" as*;
    @use"./styles/partial/variables.scss" as*;
    .p-circle-4{
        bottom: 103%;
    }
    .circle-4{
        border: #ebc4ab 8px solid;
        width: 65px;
        height: 65px ;
      
        border-radius: 50%;
        position: absolute;
    }
    #svg-5-p{
        position: absolute;
        bottom: 0%;
        z-index: 1000;
    }
    #cloud-1 {
        filter: invert(0.6);
        position: absolute;
        width: 140px;
        bottom: 81%;
      }
      #shape_1 {
        position: absolute;
        z-index: 2;
        top: 103%;
        right: 72%;
      }
      #shape_2{
        position: absolute;
        right: 70%;
      }
      #shape_3 {
        position: absolute;
        top: 247px;
        left: 46%;
        width: 31%;
      }
</style>
