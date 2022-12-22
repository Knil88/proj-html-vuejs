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
        <li v-for="link in links">
          <a href="#">
           {{ link}}&#8964;
          </a>
        </li>
       </ul>
      </div>
      <div id="logo">
        <img src="../assets/immagini/dark-logo.png" alt="">
      </div>
      <div id="nav-right">
        <font-awesome-icon icon="fa-solid fa-cart-shopping" id="icona"/><span id="numero">0</span>
        <font-awesome-icon icon="fa-solid fa-user"/>
        <input type="text" placeholder="Search..">
        <font-awesome-icon icon="fa-solid fa-magnifying-glass" id="searchLens"/>
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
      <div id="tool">
        <font-awesome-icon class="i" icon="fa-solid fa-user"/>
        <font-awesome-icon class="i" icon="fa-solid fa-user"/>
        <font-awesome-icon class="i" icon="fa-solid fa-user"/>
        <font-awesome-icon class="i" icon="fa-solid fa-user"/>
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
   background-color: #f6f6f6;;
    img{
      max-width: 100%;
      padding: 10px 0px;
    }
    #tool {
      display: flex;
      flex-direction: column;
      background-color: #ffffff;
      color: black;
      position: absolute;
      padding: 5px;
      margin: 5px 0px;
      right: 0%;
      top: 40%;
      border-radius: 12px;
    }
    .i{
      margin: 5px;
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
    margin: 0px 14px;
    font-size: 13px;
  }
  ul{
    display: flex;
  }
  #logo{
    text-align: center;
    img{
      
     max-width: 30%;
     margin-right: 247px;
    }
  }
  #numero {
    background-color: #20ad96;
    color: white;
    border-radius: 7px;
      border-top-left-radius: 7px;
      border-top-right-radius: 7px;
      border-bottom-right-radius: 7px;
      border-bottom-left-radius: 7px;
      padding: 2px 5px;
      position: absolute;
      font-size: 8px;
      text-align: center;
      bottom: 19px;
      left: 13px;
      
  }
  #nav-right{
    position: relative;
  }
  #icona{
  margin: 0px 5px;
  }
  #searchLens{
    font-size: 12px;
    position: absolute;
    color: #20ad96;
    top: 6px;
    right: 4px;
  }
  input{
    margin-left: 16px;
    padding: 5px;
    border: none;
    border-radius: 5px;
    background-color: #f5f5f5;
    outline: none;
  }


</style>
