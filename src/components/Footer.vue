<script setup lang="ts">

</script>

<template>
  <div class="footer">
    <div class="footer-container">
        <div class="footer-section footer-section-images">
            <img class="footer-image" src="../assets/logo_kv_fs.png">
            <img class="footer-image" src="../assets/logo-jrk.png">
        </div>
        <div class="footer-section">
            <a href="https://www.facebook.com/DRK.Sommercamp/" target="_blank"><li class="footer-section">Facebook</li></a>
            <a href="https://www.instagram.com/drk_sommercamp/" target="_blank"><li class="footer-section">Instagram</li></a>
            <a href="#"><li class="footer-section">Kontakt</li></a>
        </div>
        <div class="footer-section">
            <a href="https://www.drk-ov-kw.de/" target="_blank"><li class="footer-section">DRK Königs Wusterhausen</li></a>
            <a href="https://www.drk-flaeming-spreewald.de" target="_blank"><li class="footer-section">DRK Kreisverband <br> Fläming Spreewald</li></a>
            <a href="https://www.drk-flaeming-spreewald.de/spenden-projekte.html" target="_blank"><li class="footer-section">Mitglied werden</li></a>
            <a href="https://www.drk-flaeming-spreewald.de/koenigs-wusterhausen/ortsverband-koenig-wusterhausen.html" target="_blank"><li class="footer-section">Spenden</li></a>
        </div>
        <div class="footer-section">
            <a href="#" target="_blank"><li class="footer-section">Impressum</li></a>
            <a href="#" target="_blank"><li class="footer-section">AGB</li></a>
            <a href="#" target="_blank"><li class="footer-section">Datenschutz</li></a>
        </div>
    </div>
</div>
</template>

<style scoped>
    div.footer{
        width: 100%;
        background-color: #515050;
        color: white;  
        border-top: 1.5px solid black;
    }

    a{
        text-decoration: none;
        color: white;
    }

    @media only screen and (max-width: 991px) {
        div.footer-container {
        width: 90%;
        height: 100%;
        margin: auto;
        overflow: hidden;
        display: flex;
        flex-direction: column; /* Change the layout to column */
        align-items: center; /* Center align items horizontally */
        }

        div.footer-section {
            text-align: center;
            width: 100%;
            list-style-type: none;
            padding: 10px 0;
            border-bottom: 1px solid white;
        }

        div.footer-section-images {
            order: 1; /* Set the order to move this div to the bottom */
            border-bottom: none;
        }

        img {
            height: 100px;
            margin: 5%; /* Add margin to the images */
        }

        a {
            font-size: 100%;
        }

        li{
            padding: 5px;
        }

    }

    @media only screen and (min-width: 992px) {
        div.footer{
            height: 40vh;
        }
        div.footer-container{
            display: flex;
            justify-content: space-evenly;
            width: 60%;
            height: 100%;
            margin: auto;

        }
        div.footer-section{
            text-align: center;
            width: 20%;
            list-style-type: none;
            margin: 20px 0;
        }

        img{
            height: 40%;
            margin: 5%;
        }

        a{
            font-size: 120%;
        }

        li{
            padding: 10px;
        }
    }
</style>