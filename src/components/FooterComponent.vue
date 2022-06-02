<template>
    <div class="ContatoContainer">
        <div class="ContatTitulo">
            <p class="ContatoTitulo">Contato</p>
        </div>
        <div class="InformacoesContainer">
            <input type="text" placeholder="Nome" class="InputInformacoes">
            <input type="text" placeholder="E-mail" class="InputInformacoes">
            <textarea class="Mensagem" placeholder="Mensagem"></textarea>
            <button class="BtnEnviarInformacoes">Enviar Mensagem</button>
        </div>
        <div class="InformacoesContato">
            <p class="TituloInformacoes">TELEFONE</p><br>
            <p class="Informacoes">+55 (11) 3088-0757</p><br>
            <p class="TituloInformacoes">E-MAIL</p><br>
            <p class="Informacoes">renee@reneetrajar.com.br</p><br>
            <p class="TituloInformacoes">ATENDIMENTO PERSONALIZADO</p>
            <button class="BtnAtendimento">Clique aqui!</button>
        </div>
        
    </div>
    <footer>
        <div class="FooterContainer">
            <img class="ImagemFooter" src="../assets/img/ImgFooter.png" alt="ImgFooter">
            <p class="Cnpj"> CNPJ:04.487.685/0001-01</p>
            <p class="Copyright">Copyright: 2021 © Renee Trajar - Todos direitos reservados.</p>
            <a class="LinkTopo" href="#">&#9650;</a>
        </div>
    </footer>
</template>
<script>
    export default {
        name: 'FooterComponent'
    }
</script>
<style>
    .LinkTopo{
        color: rgb(255, 255, 255);
        background-color: rgb(0, 0, 0);
        box-shadow: 20px;
        display: flex;
        float: right;
        margin-bottom: 50px;
        margin-right: 25px;
    }
    .ContatTitulo{
        height: 50px;
    }
    .ContatoTitulo{
        text-align: center;
        display: block;
        position: relative;
        padding-top: 30px;
        padding-bottom: 8px; 
        font-size: 40px;
        font-weight: 100;
        border: none;
        font-family: 'Times New Roman', Times, serif;
        color: rgb(38, 70, 125);
    }.ContatoTitulo::after{
        content: '';
        position: absolute;
        bottom: 0;
        left: 700px;
        width: 25.5%;
        height: 1px;
        background-color: rgb(38, 70, 125);
        opacity: 0;
        transition: opacity 300ms, transform 300ms;
    }
    .ContatoTitulo::after {
        opacity: 1;
        transform: scale(0);
        transform-origin: center;
    }
    .ContatoTitulo:hover::after,
    .ContatoTitulo:focus::after{
        transform: scale(1);
    }
    .BtnAtendimento{
        background-color:transparent;
        border: none;
        color: rgb(23, 48, 91);
        border: 1px solid rgb(23, 48, 91);;
        width: 240px;
        height: 45px;
        font-size: 15px;
        margin-top: 20px;
        font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    }
    .BtnAtendimento:hover{
        background-color: transparent;
        transition: 0.6s;
        border: 1px solid rgb(225, 203, 80);
        color: rgb(225, 203, 80);
    }
    .InformacoesContato{
        display: flex;
        flex-direction: column;
        padding-top: 60px;
        width: 45%;
        float: left;
    }
    .InformacoesContato p{
        padding-left: 200px;
    }
    .InformacoesContato button{
        margin-left: 200px;
    }
    .InputInformacoes{
        margin-top:40px;
        float: right;
        width: 70%;
        height: 20%;
        display: flex;
        flex-direction: column;
        border-color: rgb(28, 57, 106);
        font-size: 30px;
        font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    }
    .TituloInformacoes{
        color: rgb(28, 57, 106);
        font-size: 25px;
        font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    }
    .Informacoes{
        color: rgb(110, 117, 131);
        font-size: 20px;
        font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    }
   .InformacoesContainer{
       display: flex;
        flex-direction: column;
        padding-top: 60px;
        width: 50%;
        float:right;
    }
    .Mensagem{
        margin-top: 20px;
        width: 70%;
        height: 60%;
        font-size: 30px;
        font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    }
    .BtnEnviarInformacoes{
        background-color:rgb(23, 48, 91);
        border: none;
        color: #FFF;
        width: 70%;
        margin-top: 20px;
        height: 70px;
        font-size: 25px;
        font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    }
    .BtnEnviarInformacoes:hover{
        background-color:rgb(39, 75, 138);
        transition: 0.6s;
    }
    .ContatoContainer{
        height: 460px;
    }
    .FooterContainer{
        margin-top: 65px;
        border-style: solid;
        height: 300px;
        border-top-width: 3px;
        border-bottom-width: 0px;
        border-left-width: 0px;
        border-right-width: 0px;
        border-color: rgb(205, 172, 132);
    }
    .ImagemFooter{
        padding-top: 80px;
        padding-left: 50px;
    }
    .Cnpj{
        font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
        padding-left: 141px;
        color: rgb(110, 117, 131);
        width: 600px;
    }
    .Copyright{
        font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
        float: right;
        padding-right: 60px;
    }
</style>