<script >





</script>

<template>
    <section class="white" id="big-margin">
        <section class="wrapper">
            <div class="text-container">
             
               <div class="info-title">
                <h5>
                    <span>TESTIMONIALS</span>
                </h5>
                <h1 class="titolo">
                    Why do People <span>*Hearts*</span> Us?
                </h1>
                <p>
                   Seeking for verbals of our service quality?
                   find them here.
                   Everything is trasparent and straightforward for your sense
                   of justification.
                </p>
                <div id="domande">
                     <a href="#" id="link">
                        <strong>
                            View all &RightArrow;
                        </strong>
                    </a>
                </div>
               </div>
            </div>
            <div class="poster-container">
                <div class="container-recensioni p-recensioni-1">
                    <p>
                        <strong>
                            Professional team of specialist and passionate mentor at reach
                        </strong>
                    </p>
                    <p>
                        I need to get a certification for English proficiency an MaxCoach is my best choice.Their tutors are smart and professional when deailin with students.
                    </p>
                    <div class="rounded flex " >
                        <img  src="../assets/immagini/testimonial-avata-01.jpg" alt="" >
                        <div>
                            MADLEY PONDOR
                            <div>
                               /IT Specialist
                            </div>
                        </div>
                    </div>
                </div>
                <div class="container-recensioni p-recensioni-2">
                    <p>
                        <strong>
                            The Max Coach team works really hard to ensure hugh level of quality.
                        </strong>
                    </p>
                    <p>
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Doloremque possimus repellat adipisci, distinctio, illo sunt maiores quam autem corporis dolorem vero odit dolor accusamus soluta quo fugit debitis repudiandae sequi.
                    </p>
                    <div class="rounded flex " >
                        <img  src="../assets/immagini/testimonial-avata-01.jpg" alt="" >
                        <div>
                            MADLEY PONDOR
                            <div>
                               /IT Specialist
                            </div>
                        </div>
                    </div>
                </div>
                <div class="container-recensioni p-recensioni-3">
                    <p>
                        <strong>
                            The Max Coach team works really hard to ensure hugh level of quality.
                        </strong>
                    </p>
                    <p>
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Doloremque possimus repellat adipisci, distinctio, illo sunt maiores quam autem corporis dolorem vero odit dolor accusamus soluta quo fugit debitis repudiandae sequi.
                    </p>
                    <div class="rounded flex " >
                        <img  src="../assets/immagini/testimonial-avata-02.jpg" alt="" >
                        <div>
                                MINA HOLLACE
                            <div>
                               /Freelancer
                            </div>
                        </div>
                    </div>
                </div>
            </div>
      </section>
    </section>
</template>

<style lang="scss">
    @use"./styles/general.scss" as*;
    @use"./styles/partial/variables.scss" as*;
    #domande{
        text-align: start;
    }
    #link{
        color:#171520;
        margin: 0;
      }
      .container-recensioni{
        padding: 15px;
        border-radius: 10px;
        
       
        
       box-shadow: 3px -2px 28px 5px rgba(8, 66, 125, 0.66);
        }
        p{
            padding: 5px 0px;
        }
      
      .rounded{
        display: flex;
        margin: 10px 0px;
        div{
            align-self: center;
            padding: 5px 0px;
        }
        img{
            width: 15%;
            border-radius: 50%;
        }
      }
      .poster-container{
        position: relative
      }
      .p-recensioni-1,.p-recensioni-2,.p-recensioni-3{
        position: absolute;
      }
      .p-recensioni-3 {
        opacity: 0.5;
        clip-path: inset(71.76% -99px -45px -67px);
        width: 68%;
        top: -2%;
        left: 19%;
        img{
            width: 60px;
        }
      }
      
      .p-recensioni-2{
        bottom: 22%;
        width: 68%;
        left: 18%;
        clip-path: inset(-13px -28px 59% -33px);
        opacity: 0.5;
      }
     
</style>
