<script setup lang="ts">

</script>

<template>
    <div class="header">
        <div class="navigation-image">
            <img src="../assets/logo.png" alt="Logo des DRK-Sommercamp" id="navigation-logo">
        </div>
        <div class="navigation-elements">
            <button class="navigation-element not-last">News</button> 
            <button class="navigation-element not-last">Team</button>  
            <button class="navigation-element">Video</button>
            <button class="navigation-element-spotlight">Jetzt <br> Anmelden!</button>
        </div>
        
    </div>
  
</template>

<style scoped>
    div.header{
        margin: auto;
        overflow: hidden;
        display: flex;
        align-items: center;
    }

    div.navigation-image{
        height: 100%;
        display: block;
    }

    div.navigation-elements{
        height: 100%;
        width: 100%;
        display: flex;
        align-items: center;
        justify-content: right;
    }
    
    #navigation-logo{
        height: 100%;
        cursor: pointer;
    }

    button {
        cursor: pointer;
    }

    button.navigation-element{
        background-color: white;
        font-weight: bold;
        border: 0;
    }

    button.not-last{
        border-right: 1px solid black;
    }

    button.navigation-element-spotlight{
        font-weight: bold;
        background-color: #FFD100;
        border-radius: 5px;
    }

    @media only screen and (max-width: 991px) {
        div.header{
            height: 10vh;
            width: 100%;
        }

        button{
            font-size: 100%;
        }

        button.navigation-element-spotlight{
            margin: 5px;
            padding: 5px;
        }
        button.navigation-element{
            padding: 5px;
        }
    }

    @media only screen and (min-width: 992px) {
        div.header{
            height: 20vh;
            width: 60%;
        }

        button{
            font-size: 200%;
        }

        button.navigation-element-spotlight{
            margin: 20px;
            padding: 15px;
        }

        button.navigation-element{
            padding: 10px;
        }
    }

</style>
