<script >





</script>

<template>
 <section>
    <div class=" center">
        <h5 id="sottotitolo">
           JOIN MAX COACH AT BEST
        </h5>
        <h1 class="titolo">
           Latest online  <span>Courses</span> 
        </h1>
        <div class="course-row">
            <div class="course-card course-container">
                <img src="../assets/immagini/course-02-480x298.jpg" alt="">
                <div class="info-offer " id="start">
                   <h3  class="info-offer">
                    $40.<span>00</span>
                   </h3>
                   <div class="info-offer " id=" course-description">
                    Learning to Write as a Professional Author
                   </div>
                   <div class="icon-row  info-offer">
                    <font-awesome-icon class="i" icon="fa-solid fa-user" />
                    <div class="description">
                       20 Lessons
                    </div>
                    <font-awesome-icon class="i" icon="fa-solid fa-user"/>
                    <div class="description">
                        50 Students
                    </div>
                   </div>
                </div>
            </div>
            <div class="course-card course-container">
                <img src="../assets/immagini/stock-full-hd-03-480x298.jpg" alt="">
                <div class="info-offer " id="start">
                   <h3  class="info-offer">
                    $00.<span>00</span>
                   </h3>
                   <div class="info-offer " id=" course-description">
                   Customer-centric Info-Tech Strategies
                   </div>
                   <div class="icon-row  info-offer">
                    <font-awesome-icon class="i" icon="fa-solid fa-user" />
                    <div class="description">
                       24 Lessons
                    </div>
                    <font-awesome-icon class="i" icon="fa-solid fa-user"/>
                    <div class="description">
                        769 Students
                    </div>
                   </div>
                </div>
            </div>
            <div class="course-card course-container">
                <img src="../assets/immagini/stock-full-hd-04-480x298.jpg" alt="">
                <div class="info-offer " id="start">
                   <h3  class="info-offer">
                    $19.<span>00</span>
                   </h3>
                   <div class="info-offer " id=" course-description">
                   Open Programming Courses for Everyone:Python
                   </div>
                   <div class="icon-row  info-offer">
                    <font-awesome-icon class="i" icon="fa-solid fa-user" />
                    <div class="description">
                       17 Lessons
                    </div>
                    <font-awesome-icon class="i" icon="fa-solid fa-user"/>
                    <div class="description">
                        62 Students
                    </div>
                   </div>
                </div>
               
            </div>
      
           
        </div>
        <div class="icon-row  info-offer position-3">
            <font-awesome-icon class="i m-2" id="big" icon="fa-solid fa-circle" />
            <font-awesome-icon class="i m-2" icon="fa-solid fa-circle" />
            <font-awesome-icon class="i m-2" icon="fa-solid fa-circle" />
            <font-awesome-icon class="i m-2" icon="fa-solid fa-circle" />
            <font-awesome-icon class="i m-2" icon="fa-solid fa-circle" />
           
            
        </div>
        <p id="p-position">
           <strong>
            Control your personal preference settings to get notified about <br> appropriate courses.
           </strong> <span>
                <a href="#"><strong>
                    View all courses &RightArrowBar;
                </strong></a>
            </span>
        </p>
       </div>
      
 </section>
 <img id="wawe" src="../assets/svg-1.svg" alt="">
</template>

<style lang="scss">
    @use"./styles/general.scss" as*;
    @use"./styles/partial/variables.scss" as*;
    .course-row{
        display: flex;
        width: 80%;
        margin: auto;
       
        
    }
    .center{
        text-align: center;
        h5{
           color: #6c6c6b;
        }
    }
    .info-offer{
        text-align: start;
        padding: 10px ;
        h3{
             color:#20ad96;
            span{
                font-size: 12px;
            }
        }
    }
    .icon-row{
        display: flex;
        font-size: 10px;
        color:#21ad96 ;
    }
    .description{
        margin: 0px 10px;
    }
    .course-container{
        margin: 30px;
        img{
            max-width: 100%;
            border-radius: 5px;
        }
    }
    #course-description{
        color:#323232;
    }
    .position-3{
        position: absolute;

        left:43%;
       

    }
    .m-2{
        margin: 0px 10px;
        color: #d8d8d8;
        align-self: center;
    }
    #big{
        font-size: 15px;
        color: black;
    }
    #wawe{
        filter: invert(1);
        width: 100%;
        max-height: 57px;
        position: relative;
        top: 4px;
    }
    #p-position{
        margin-top: 5%;
        color:#696969;
        font-size: 13px;
    }
</style>
