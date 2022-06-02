<template>
    <main>
        <div>
            <img class="ReneeImage" src="../assets/img/renee.png">
            <div class="ContainerTrajar">
                <a class="TextoTitulo">Renee Trajar</a><br><br><br>
                <p class="TextoDescricao">
                    Com mais de 35 anos de experiência em camisas, calças e ternos sob medida, possuímos<br>profissionais experientes e altamente qualificados.<br><br>
                    Cada cliente tem seu molde exclusivamente desenvolvido para seu biotipo através das<br>medidas tiradas pelo próprio Sr. Renee, no escritório ou residência do cliente.<br><br>
                </p>
                    <p class="TextoDepoimento"><i>"Nosso objetivo é superar a expectativa do cliente proporcionando-lhe satisfação<br>ao usar nossos produtos, aliado a um relacionamento franco e honesto,<br>valorizando o ser humando."</i></p>
                    <p class="AssinaturaRenee">Renee Trajar</p>
                <button class="VisitaBtn">Agende uma visita!</button>
            </div>
        </div>
        <div class="NelsonBlueContainer">
            <img class="NelsonBlue" src="../assets/img/Nelson1.png">
            <p class="AvaliacaoNelson">"Faço roupas com o Renee Trajar há mais de duas décadas, o<br>serviço é impecável em todos os detalhes, desde a costura ao<br>caimento. O Renee tem uma equipe de mestre!"</p>
            <p class="NomeNelson"><i>Nelson Garey</i></p><br>
            <p class="ProfissaoNelson">Advogado | Nelson Garey Advogados Associados</p>
        </div>
        <div class="NelsonDiagonalContainer">
            <img class="NelsonDiagonal" src="../assets/img/Nelson2.png">
        </div>
        <div class="AtributosContainer">
            <div class="CosturaContainer">
                <img class="ImgCostura" src="../assets/img/Costura.jpg">
                <p class="TituloCostura">QUALIDADE</p>
                <p class="TextoCostura">Camisaria e Alfaiataria 100% artesanal.</p>
            </div>
            <div class="AgulhaContainer">
                <img class="ImgAgulha" src="../assets/img/Agulha.png">
                <p class="TituloAgulha">EXPÊRIENCIA</p>
                <p class="TextoAgulha">Tradição e modernidade proporcionando elegância.</p>
            </div>
            <div class="SeloContainer">
                <img class="ImgSelo" src="../assets/img/Selo.png">
                <p class="TituloSelo">CONFIANÇA</p>
                <p class="TextoSelo">Atendimento personalizado no escritório ou residência</p>
            </div>
        </div>
    </main>
    <article>
        <div class="PromocaoContainer">
            <img class="PessoaVestidaAzul" src="../assets/img/Ternoazul.png">
            <p class="TituloCondicao">Condição Imperdível</p>
            <p class="SubTituloCondicao"><i>Compre hoje e garanta:</i></p>
            <p class="TextoCondicao">
                <span>-</span> 12% de desconto e pagamento em até <strong>3x sem juros;</strong><br>
                <span>-</span> Até <strong>10 meses</strong> para confeccionar sua roupa. Não se preocupe se<br>
                <a>suas medidas aumentaram ou diminuíram, estará sempre elegante;<br></a>
                <span>-</span> Condição muito especial por <strong>tempo limitado;</strong><br>
                <span>-</span> Poder presentear alguém com uma roupa de alta costura, <strong>exlusiva.</strong>
            </p>
            <button class="BtnCondicao">Garanta essa condição especial!</button>
        </div>
        <div class="ServicosContainer">
            <div class="ImagemContainer">
                <img class="CamisaBranca" src="../assets/img/CamisaBranca.png">
            </div>
            <div class="PrimeiraLista">
                <p class="TituloCamisaria">CAMISARIA</p>
                <p class="SubTituloCamisaria">- CONFECCIONADAS ARTESANALMENTE</p>
                <ul class="Lista">
                    <li><i>100% Algodão</i></li>
                    <li><i>Monograma</i></li>
                    <li><i>Slim</i></li>
                </ul>
                <ul class="Lista">
                    <li><i>Nacionais e Importados</i></li>
                    <li><i>Tradicionais e Esportivas</i></li>
                    <li><i>Casamentos</i></li>
                </ul>
                <button class="BtnLista">Quero um orçamento</button>
            </div>
            <div class="ImagemContainer2">
                <img class="TernoCinza" src="../assets/img/TernoCinza.png">
            </div>
            <div class="SegundaLista">
                <p class="TituloAlfaiataria">ALFAIATARIA</p>
                <p class="SubTituloAlfaiataria">- TOTALMENTE FEITO A MÃO SOB MEDIDA</p>
                <ul class="Lista">
                    <li><i>Fio Super 120 e 130</i></li>
                    <li><i>Lã fria Australiana</i></li>
                    <li><i>Botões Importados</i></li>
                </ul>
                <ul class="Lista">
                    <li><i>Ternos e Calças</i></li>
                    <li><i>Paletós e Smokings</i></li>
                    <li><i>Sociais e Esportivos</i></li>
                </ul>
                <button class="BtnLista">Quero um orçamento</button>
            </div>
        </div>
        <div class="CarroContainer">
            <p class="TituloDepoimentos">Depoimentos</p>
            <carrossel-component/>
        </div>
    </article>
  
</template> 


<script>

    
    import CarrosselComponent from './CarrosselComponent.vue'

    export default {
        name: 'BodyComponent',
        components: {
        CarrosselComponent,
    
}
    }

</script>


<style>
    .ReneeImage{
        padding-top: 58px;
        padding-left: 220px;
        width: 390px;
    }
    .ContainerTrajar{
        float: right;
        padding-right: 115px;
        padding-top: 55px;
        color: rgb(23, 48, 91);
    }
    .TextoDescricao{
        color: black;
        font-weight: 100;
        font-size: 30px;
    }
     .TextoTitulo{
        font-size: 33px;
        font-weight: 100;
        border: none;
        font-family: 'Times New Roman', Times, serif;
        color: rgb(38, 70, 125);
        display: block;
        position: relative;
        padding: 0.2em 0;
    }
    .TextoDepoimento{
        font-size: 35px;
        font-weight: 100;
        color: rgb(38, 70, 125);
        font-family:unset;
        margin-bottom: 20px;
    }
    .TextoTitulo::after{
        content: '';
        position: absolute;
        bottom: 0;
        left: -55px;
        width: 25.5%;
        height: 1px;
        background-color: rgb(38, 70, 125);
        opacity: 0;
        transition: opacity 300ms, transform 300ms;
    }
    .TextoTitulo::after {
        opacity: 1;
        transform: scale(0);
        transform-origin: center;
    }
    .TextoTitulo:hover::after,
    .TextoTitulo:focus::after{
        transform: scale(1);
    }
    .AssinaturaRenee{
        color:rgb(157, 121, 77);
        float: right;
        font-size: 28px;
        padding-right: 150px;
    }
    .NelsonBlueContainer{
        margin-top: 85px;
        background-color: rgb(245, 252, 249);
        height: 450px;
        position:relative; 
        top:0px; 
        left:0px
    }
    .NelsonBlue{
        float: right;
        height: 100%;
        position: relative;
    }
   .NelsonDiagonalContainer{
       margin-top: 35px;
       position:absolute; 
       top: 1145px; 
       height: 450px;
   }
   .NelsonDiagonal{
       position:relative; 
       right: -1290px;
       height: 100%;
   }
   .AvaliacaoNelson{
       text-align: center;
       padding-top: 120px;
       font-size: 34px;
       color:rgb(131, 131, 131);
       font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
   }
   .NomeNelson{
        text-align: center;
        font-size: 34px;
        color: rgb(38, 70, 125);
        padding-top: 30px;
   }
    .ProfissaoNelson{
        color: rgb(222, 192, 155);
        text-align: center;
        font-size: 32px;
        font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    }
    .VisitaBtn{
        background-color:rgb(23, 48, 91);
        border: none;
        color: #FFF;
        width: 400px;
        height: 70px;
        font-size: 25px;
        font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    }
    .VisitaBtn:hover{
        background-color:rgb(12, 30, 62);
        transition: 0.7s;
    }
    .CosturaContainer{
        float: left;
        display: flex;
        width: 634px;
        height: 300px;
        align-items: center;
        justify-content: center;
        flex-direction: column;
    }
    .ImgCostura{
        width: 70px;
        height: 70px;
    }
    .AgulhaContainer{
        float: right;
        display: flex;
        width: 634px;
        height: 300px;
        align-items: center;
        justify-content: center;
        flex-direction: column;
    }
    .ImgAgulha{
        width: 70px;
        height: 70px;
    }
    .SeloContainer{
        float: right;
        display: flex;
        width: 634px;
        height: 300px;
        align-items: center;
        justify-content: center;
        flex-direction: column;
    }
    .ImgSelo{
        width: 70px;
        height: 70px;
    }
    .TituloCostura{
        font-size: 32px;
        color: rgb(23, 48, 91);
        padding: 8px;
    }
    .TextoCostura{
        font-size: 20px;
        color: rgb(222, 192, 155);
        font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    }
    .TituloSelo{
        font-size: 32px;
        color: rgb(23, 48, 91);
        padding: 8px;
    }
    .TextoSelo{
        font-size: 20px;
        color: rgb(222, 192, 155);
        font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    }
    .TituloAgulha{
        font-size: 32px;
        color: rgb(23, 48, 91);
        padding: 8px;
    }
    .TextoAgulha{
        font-size: 20px;
        color: rgb(222, 192, 155);
        font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    }
    .AtributosContainer{
        width: 1920px;
        height: 310px;
    }
    .PromocaoContainer{
        background-color: rgb(8, 57, 74);
        height: 700px;
    }
    .PessoaVestidaAzul{
        float: right;
        padding-top: 50px;
        padding-right: 170px;
        height: 600px;
    }
    .TituloCondicao{
         color: rgb(222, 192, 155);
         font-size: 78px;
         padding-top: 70px;
         padding-left: 200px;
    }
    .SubTituloCondicao{
         color: rgb(222, 192, 155);
         font-size: 40px;
         padding-left: 200px;
         padding-top: 30px;
    }
    .TextoCondicao{
        color: #FFF;
        font-size: 30px;
        font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
        padding-left: 100px;
    }
    .TextoCondicao a{
        color: #FFF;
        font-size: 30px;
        font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
        padding-left: 100px;
    }
    .TextoCondicao span{
        color: rgb(222, 192, 155);
        font-size: 50px;
        padding-left: 100px;
    }
    .BtnCondicao{
        background-color:rgb(182, 147, 105);
        border: none;
        color: #FFF;
        width: 400px;
        height: 70px;
        font-size: 25px;
        font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
        margin-left: 200px;
        margin-top: 25px;
    }
    .BtnCondicao:hover{
        background-color:rgb(109, 109, 109);
        transition: 0.7s;
    }
    .CamisaBranca{
        padding-left: 400px;
        padding-top: 100px;
        width: 650px;
    }
    .TernoCinza{
        float: right;
        padding-top: 95px;
        padding-right: 400px;
        width: 650px;
    }
    .ServicosContainer{
        height: 1360px;
        flex-direction:row;
    }
    .PrimeiraLista{
        border-style: solid;
        border-bottom-width: 1px;
        border-top-width: 1px;
        border-right-width: 1px;
        border-left-width: 0;
        float: right;
        padding: 80px;
        display: flex;
        flex-direction: column;
        margin-right: 200px;
        margin-top: -540px;
    }
    .PrimeiraLista ul{
        align-items: center;
    }
    .Lista{
        padding-left: 15px;
        font-size: 20px;
        color: rgb(109, 109, 109);
    }
    .Lista:first-of-type{
        padding-top: 25px;
    }
    .ImagemContainer{
        width: 950px;
    }
    .TituloCamisaria{
        font-size: 60px;
        color: rgb(8, 57, 74);
    }
    .SubTituloCamisaria{
        font-size: 30px;
        color: rgb(109, 109, 109);
        font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    }
    .SegundaLista{
        border-style: solid;
        border-bottom-width: 1px;
        border-top-width: 1px;
        border-left-width: 1px;
        border-right-width: 0;
        padding: 80px;
        margin-left: 300px;
        margin-top: 120px;
        display: flex;
        flex-direction: column;
        width: 699px;
    }
    .TituloAlfaiataria{
        font-size: 60px;
        color: rgb(8, 57, 74);
    }
    .SubTituloAlfaiataria{
        font-size: 30px;
        color: rgb(109, 109, 109);
        font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    }
    .BtnLista{
        background-color:rgb(23, 48, 91);
        border: none;
        color: #FFF;
        width: 300px;
        margin-top: 20px;
        height: 70px;
        font-size: 25px;
        font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    }
    .BtnLista:hover{
        background-color: rgb(9, 27, 58);
        transition: 0.9s;
    }
    .CarroContainer{
        text-align: center;
        background-color:  rgb(17, 43, 87);
    }
    .TituloDepoimentos{
        display: block;
        position: relative;
        padding-top: 30px;
        padding-bottom: 8px; 
        font-size: 40px;
        font-weight: 100;
        border: none;
        font-family: 'Times New Roman', Times, serif;
        color: #FFF;
    }.TituloDepoimentos::after{
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
    .TituloDepoimentos::after {
        opacity: 1;
        transform: scale(0);
        transform-origin: center;
    }
    .TituloDepoimentos:hover::after,
    .TituloDepoimentos:focus::after{
        transform: scale(1);
    }

   
</style>