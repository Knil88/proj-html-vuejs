<script >





</script>

<template>
    <section class="wrapper">
       
        <div class="poster-container">

          
            <div>
                <div class="img-container">
                   <img class="cloud" src="../assets/svg-0.svg" alt="">
                </div>
                <div class="img-container">
                    <img src="..//assets/immagini/maxcoach-shape-05-150x150.png" alt="" id="shape-position">
                </div>
                <div class="img-container">
                    <img src="../assets/immagini/icon-youtube-play.png" alt="" id="play-position">
                </div>
                <div class="img-container">
                    <img src="../assets/immagini/stock-full-hd-11-670x450.jpg" alt="" id="full-image">
                </div>
                <div class="img-container">
                    <img  src="../assets/immagini/maxcoach-shape-07-150x150.png" alt="" id="svg-position-3" >
                </div>
            </div>
        </div>
        <div class="text-container">
            <div class="circle-container position">
                <div class="circle-3 p-circle-2">
            </div>
              
            </div>
            <div class="circle-container position-2">
                <div class="circle-2 p-circle-3">
                   
                </div>

            </div>
           <div class="info-title">
            <h5>
                HOW WE WORK
            </h5>
            <h1 class="titolo">
                Upgrade Your Skills <span>Upgrade Your Life</span> at Max Coach
            </h1>
            <p>
                Opening up more opportunities in front of you to get the ticket to more enjoyable door in life.Getting equipped with new skills for new sets of insights into your career. <br>
                MaxCoach accompany learners in every stage of learning.
            </p>
            <div>
                 <a href="#" id="link">
                    <strong>
                        Download Free Guide &RightArrow;
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
    z-index: 1000;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    cursor: pointer;
}
  #link{
    color:#171520;
    margin: 0;
  }
  #shape-position{
    position: absolute;
    bottom: 44%;
    right: 85%;
  }

  #full-image{
    z-index: 1;
    position: relative;
  }
  .p-circle-2{
    bottom: 91%;
    left: 0%;
  }
  .p-circle-3{
    clip-path: inset(27% 0 0 0);
  }
 
  .circle-container, .circle-container-1{
  
    position: absolute;
    
  }
  .circle-container{

  }
  .position{
    right: 91%;
    bottom: 93%;
    
  }
  .position-2{
    bottom: 92%;
  }
  .circle-2,.circle-3{
        border: #ebc4ab 8px solid;
        width: 50px;
        height: 50px ;
       
        background-color: white;
        border-radius: 50%;
  }
  .circle-3{
    
    clip-path: inset(0 0 59% 0);
  }
  #svg-position-3{
    position: absolute;
    left: 73%;
    top: 66%;
  }
</style>
