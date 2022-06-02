<template>
    <div class="slider">
        <input type="radio" name="slider" id="slide1" checked>
        <input type="radio" name="slider" id="slide2">
        <input type="radio" name="slider" id="slide3">
        <input type="radio" name="slider" id="slide4">
        <div class="slides">
            <div class="overflow">
                <div class="inner">
                    <div class="slide slide_1">
                        <img src="../assets/img/AvaliadorUm.png" alt="AvaliadorUm">
                        <p class="Desc"><i>"Sou cliente do Renee há uns 12 anos. Nosso primeiro contato foi por interédio de<br>meu pai, que já tem uma história de décadas com o querido Renee.<br>O excelente atendimento antes e pós venda e a alta qualidade dos materiais usados<br>colocam a Renee Trajar em um patamar acima dos demais do ramo."</i></p>
                        <p class="Nome">WIlliam H. M. Garey</p>
                        <p class="Profi">Advigado | Nelson Garey Advogados Associados</P>
                    </div>

                    <div class="slide slide_2">
                        <img src="../assets/img/AvaliadorDois.png" alt="AvaliadorDois">
                        <p class="Desc"><i>"Seu corre tanto de camisas, bem como de ternos são impecáveis, muitos dos<br>meus amigos tem elogiado a vestimenta.<br>Recomendo para quem gosta de perfeição. Estamos nos servindo do trabalho do<br>Renee Trajar há mais de vinte anos."</i></p>
                        <p class="Nome">Domingos Orestes Chiomento</p>
                        <P class="Profi">DOC Contabilidade Empresarial</P>
                    </div>

                    <div class="slide slide_3">
                        <img src="../assets/img/AvaliadorTres.png" alt="AvaliadorTres">
                        <p class="Desc"><i>"Tenho a honra de afirmar que enquanto nossas vidas perdurarem o meu conceito<br>é sempre melhor em relação ao Renee Trajar, sua pessoa, ao profissional<br>competente e indôneo, sempre pontual, atencioso e preocupado em atender da<br>melhor maneira os anseios de seus clientes, incluindo este signatário."</i></p>
                        <p class="Nome">José Mauro Marques</p>
                        <P class="Profi">Advogado</P>
                    </div>

                    <div class="slide slide_4">
                        <img src="../assets/img/AvaliadorQuatro.png" alt="AvaliadorQuatro">
                        <p class="Desc"><i>"Conheço o excelente e qualificado trabalho do Renee Trajar e sua equipe há décadas.<br>Para camisas e ternos, o Renee é imbatível, sempre com preços justos, produtos de excelente<br>qualidade e especialmente tudo é feito com muito cuidado e qualidade. Cumpre os prazos<br>com atendimento de alto nível. O Renee trabalha com perfeição nos detalhes"</i></p>
                        <p class="Nome">Custódio Pereira</p>
                        <P class="Profi">Membro do CONSOCIAL - Conselho Superior de Responsabilidade Social da FIESP-SP</P>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="controls">
        <label for="slide1"></label>
        <label for="slide2"></label>
        <label for="slide3"></label>
        <label for="slide4"></label>
    </div>
    <div class="bullets">
        <label for="slide1"></label>
        <label for="slide2"></label>
        <label for="slide3"></label>
        <label for="slide4"></label>
    </div>
</template>

<script>

    export default {
        name: 'CarrosselComponent',
    }

    
</script>

<style>
    .Desc{
        padding-top: 20px;
        color: #FFF;
        font-size: 1.5rem;
    }
    .Nome{
        color:rgb(182, 147, 105);
        padding-top: 1px;
        font-size: 1.2rem;
        height: 30px;
    }
    .Profi{
        color: #FFF;
        font-size: 1rem;
        padding-top: 3px;
        padding-bottom: 25px; 
    }
</style>