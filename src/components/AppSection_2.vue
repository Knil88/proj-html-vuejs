<script >





</script>

<template>
    <section>
        <div class="row">
            <div class="card">
             <h1>129</h1>
             <div>ENROLLED LEARNERS</div>
            </div>
            <div class="card">
                <h1>80</h1>
                <div>FINISHED SESSIONS</div>
               </div>
               <div class="card">
                <h1>4%</h1>
                <div>SATISFACTION RATE </div>
               </div>
         </div>
      </section>
</template>

<style lang="scss">
    @use"./styles/general.scss" as*;
    @use"./styles/partial/variables.scss" as*;
    .row{
        display: flex;
        justify-content: space-between;
        color: #3eaf96;
        text-align: center;
        width: 50%;
        margin: auto;
        
    }
    .card{
        margin: 0px 10px;
        h1{
            font-size: 45px;
        }
        div{
            color: #696969;
        }
    }
</style>
