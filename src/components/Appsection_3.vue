<script >





</script>

<template>
    <section class="wrapper">
       
        <div class="poster-container">

          
            <div>
                <div class="img-container">
                    <img src="../assets/immagini/icon-youtube-play.png" alt="" id="play-position">
                </div>
                <div class="img-container">
                    <img src="../assets/immagini/stock-full-hd-11-670x450.jpg" alt="">
                </div>
            </div>
        </div>
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
  </section>
</template>

<style lang="scss">
@use"./styles/general.scss" as*;
@use"./styles/partial/variables.scss" as*;
#play-position{
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    cursor: pointer;
}
  
</style>
