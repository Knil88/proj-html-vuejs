<script >





</script>

<template>
    <main>
        <section class="wrapper">
            <div class="right-container">

            </div>
            <div class="left-container">

            </div>
        </section>
    </main>
</template>

<style lang="scss">
    @use"./styles/general.scss" as*;
    @use"./styles/partial/variables.scss" as*;
    .wrapper{
        display: flex;
        width: 80%;
        margin: auto;
        height: 450px;
        .right-container{
            background-color: red;
            width: 45%;
           
        }
        .left-container{
            background-color: blue;
            width: 45%;
        }
    }
</style>
