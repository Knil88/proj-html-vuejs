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
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    cursor: pointer;
}
  #link{
    color: black;
  }
</style>
