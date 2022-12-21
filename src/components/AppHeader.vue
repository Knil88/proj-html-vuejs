<script >
export default{
  data() {
    return {
      links:["Home","Pages","Courses","Feautures","Blog","Shop"]
    }
  },
}




</script>

<template>
  <header>
    <nav>
      <div>
        <ul>
          <li>
            <a href="#">
              link 	&#8964;
            </a>
          </li>
        </ul>
      </div>
    </nav>
    <div id="jumbo">
      <div id="titolo">
        <h4>
          <strong>
            Commence Business
          </strong>
        </h4>
        <h1>
          Distant Mentoring Program
        </h1>
        <button class="btn" id="download">
          Download free guidebook &RightArrow;
        </button>
      </div>
      <img src="../assets/immagini/home-3-hero-bg.jpg" alt="">
    </div>
      
     
        
    
   
  </header>
</template>

<style lang="scss">
  @use"./styles/general.scss" as*;
  @use"./styles/partial/variables.scss" as*;
  #jumbo{
   position: relative;
   width: 100%;
    img{
      max-width: 100%;
      padding: 10px 0px;
    }
   
  }
  #titolo{
    position: absolute;
    color: white;
    text-align: center;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
  }
  #download{
    background-color: #ffffff;
    color: #20ad96;
    margin: 10px;
  }
  a{
    text-decoration: none;
    color: #3f3a64;
  }
  ul{
    display: flex;
  }
  
</style>
