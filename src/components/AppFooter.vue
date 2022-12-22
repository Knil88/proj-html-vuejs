<script >
export default{
    data() {
        return {
            
        }
    },
}




</script>
    
<template>
    <footer>
        <div class="flex-footer">
          <div>
            <ul>
                <li>
                    <h4>Address</h4>
                </li>
                <li>
                    link
                </li>
                <li>
                    link
                </li>
                <li>
                    link
                </li>
                <li>
                    link
                </li>
            </ul>
          </div>
        </div>
    </footer>
</template>

<style lang="scss">
    @use"./styles/general.scss" as*;
    @use"./styles/partial/variables.scss" as*;
    footer{
        background-color: #171621;
        color: #aba290;
        
    }
    .flex-footer{
        display: flex;
        width: 80%;
        margin: auto;
        padding: 20px 0px;
        h4{
            color: #fff;
        }
    }
</style>
