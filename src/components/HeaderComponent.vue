<template>
    <div class="BackgroundImage">
        <div class="nav">
            <img class="ImageLogo" src="../assets/img/logo.png">
            <a class="btnf" href="">CONTATO</a>
            <a class="btnf" href="">DEPOIMENTOS</a>
            <a class="btnf" href="">ALFAIATARIA</a>
            <a class="btnf" href="">CAMISARIA</a>
            <a class="btnf" href="">EMPRESA</a>
        </div>
        <div class="ContainerSlogan">
            <h2 class="h21"><i>Elegante é ter um</i></h2>
            <h1>ALFAIATE</h1>
            <h2 class="h22"><i>para chamar de seu.</i></h2>
        </div>
        <div class="ContainerOrcamento">
            <h3>COMPRE HOJE, <strong>PAGUE EM ATÉ 3X<br>COM 12% DE DESCONTO</strong> E TENHA <br>10 MESES PARA CONFECCIONAR!</h3>
            <button class="OrcamentoBtn">FAÇA JÁ UM ORÇAMENTO</button>
        </div>
        <img src="../assets/img/Whatas.png" class="WhatsImg" alt="ImagemWhats">
    </div>
</template>

<script>
   
    export default {
        name: 'HeaderComponent'
    }
</script>

<style>
    *{
        padding: 0;
        margin: 0;
    }
    .WhatsImg{
        display: flex;
        width: 50px;
        height: 50px;
        padding-left: 1800px;
        position: fixed;
        background-size: cover;
    }
    .ImageLogo{
        padding-left: 38px;
        padding-top: 25px;
    }
    .BackgroundImage{
        width: 100%;
        height: 575px;
        background-image: url("../assets/img/princ.jpg");
        background-repeat: no-repeat;
        background-size: cover;
        background-position: center center; 
    }
    .btnf{
        padding: 10px;
        float: right;
        padding-top: 25px;
        text-decoration: none;
        padding-left: 25px;
    }
    .btnf:first-of-type{
        padding: 10px;
        float: right;
        padding-top: 25px;
        text-decoration: none;
        padding-right: 70px;
    }
    .nav{
        color: #FFF;
        font-family:-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
        width: 100%; 
        position: fixed;
    }
    .nav :visited{
        color: #FFF;
        text-decoration: none;
    }
    .nav :hover{
        color: rgb(87, 142, 197);
        transition: 0.9s;
        text-decoration: none;   
    }
    .ContainerSlogan{
        padding-top: 80px;
        padding-left: 190px;
    }
    h1{
        color:rgb(23, 48, 91);
        font-size: 80px;
        padding-left: 60px;
    }
    .h21{
        font-size: 30px;
        color:rgb(170, 145, 104);
        padding-left: 60px;
    }
    .h22{
        font-size: 30px;
        color:rgb(170, 145, 104);
        padding-left: 205px;   
    }
    h3{
        color:#FFF;
        font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
        font-weight: 100;
        font-size: 21px;
    }
    .ContainerOrcamento{
        padding-left: 250px;
        padding-top: 50px;
    }
    .OrcamentoBtn{
        background-color:rgb(23, 48, 91);
        border: none;
        color: #FFF;
        width: 240px;
        height: 45px;
        font-size: 15px;
        margin-top: 20px;
        font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    }
    .OrcamentoBtn:hover{
        background-color: black;
        transition: 0.6s;
        border: 1px solid rgb(242, 251, 76);
    }

</style>