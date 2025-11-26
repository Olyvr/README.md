# Presente

<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Presente</title>
        
    <style>
       body{
        background-color: red;
        text-align: center;
    
    }
        .painel{
        padding-top: 20px;
        margin: auto;
        width: 500px;
        height: 570px;
        background-color: white;
        border-radius: 20px;
        
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    }
    
    .nova-pagina {
        display: none; /* Inicialmente escondida */
        padding: 20px; /* Ajustei para padding geral */
        margin: auto;
        width: 90%; /* Estende para ocupar mais largura */
        max-width: 600px; /* Limita a largura máxima para não ficar excessivo */
        height: auto; /* Altura automática para se ajustar ao conteúdo */
        background-color: white;
        border-radius: 20px;
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
        text-align: center;
    }
    
    h1{
      font-size: 500;

    }
    
    #sim{
        
        width: 80px;
        height: 60px;
        border-radius: 10px;
        background-color: red;
        color: bisque;
        font-size: 25px;
        margin-left: -90px;
        
        
    }
    #nao{
        position: absolute;
        width: 80px;
        height: 60px;
        border-radius: 10px;
        background-color: red;
        color: bisque;
        font-size: 25px;
        margin-left: 10px;
        
    }

    textarea {
        width: 80%;
        height: 100px;
        margin-top: 20px;
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    }

    img {
        max-width: 100%; /* Garante que o GIF não ultrapasse a largura da div */
        height: auto; /* Mantém a proporção */
        display: block; /* Remove espaço extra abaixo da imagem */
        margin: 10px auto; /* Centraliza horizontalmente e adiciona margem vertical para espaçamento */
    }

    .decoracao-superior {
        position: fixed;
        top: 10px;
        left: 10px;
        width: 80px;
        height: auto;
        opacity: 0.7; /* Para ser uma decoração leve */
        z-index: 1;
    }

    .decoracao-inferior {
        position: fixed;
        bottom: 10px;
        right: 10px;
        width: 80px;
        height: auto;
        opacity: 0.7; /* Para ser uma decoração leve */
        z-index: 1;
    }


    </style>

</head>
<body>

    <div class="painel" id="painel-principal">
        <h1>Bom dia, boa tarde e boa noite senhorita Camile (voce nao me disse oficialmente seu nome, então suponho que seja esse)</h1>
        <img src="https://cdn.pixabay.com/animation/2024/07/19/00/09/00-09-35-674_512.gif">
        <h2>Aceita um presente???</h2>


    <button id="sim" onclick="mostrarNovaPagina()"> Sim! </button>
    <button onmouseover= "fuja()" id="nao"> Não! </button>


</div>

<div class="nova-pagina" id="nova-pagina">
    <img src="https://i.pinimg.com/originals/44/30/7e/44307eb4a120068376a9997215ae85f3.gif" class="decoracao-superior" alt="Decoração Superior">
    <img src="https://i.pinimg.com/originals/f8/46/bd/f846bd9b4e24d10c5415262af6fc8ef4.gif" class="decoracao-inferior" alt="Decoração Inferior">
    <h1>QUE BOM QUE VOCÊ ACEITOOOU!!!!!</h1>
    <img src="https://i.pinimg.com/originals/dc/d2/88/dcd288ea5b0df65020fd95f2f913e906.gif" alt="Presente">
    <img src="https://i.pinimg.com/originals/bb/2b/f8/bb2bf890a3dbb278270fa3c76297bf50.gif" alt="Presente1">
    <img src="https://i.pinimg.com/originals/67/30/9c/67309cb03d822460e1e5579b202dd5cc.gif" alt="Presente2">
    <img src="https://i.pinimg.com/originals/08/23/00/08230018e8f43f67ab2692ba22a08460.gif" alt="Presente4">
    <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEiLUcDK05sY35BFvoOck_FxjW0xbsgZJk3EPUW5x2s_kBREDd0vom0BMBlCtVmhesQhoENRceKcEDGkf0PNe-ZGsPVSG9X992_ivCTtYcdnic_k91VlmO7TEqBU6dZXbenyKSHwaRc9alU/s1600/145.gif" alt="Presente3">
    <h2>Isso é por eu ter te feito chorar tocando naquele assunto aquele dia (desculpa aliás, fiquei preocupado, não gostei nem um pouco de ter te feito chorar), eu queria mandar elas fisicas, mas a logística ainda ta meio complicada, mas daqui pro seu niver eu resolvo esse problema e mando elas fisicamente ta? Essas não são a mesma coisa mas são de coração e eu achei que vc fosse gostar kk<br> (Eu n sabia sua cor nemm flor favorita, entao coloquei uma de cada)</h2>
    
</div>

<script>

    function fuja(){
        var botaoNao = document.getElementById("nao")
        
        var larguraJanela = window.innerWidth;
        var alturaJanela = window.innerHeight;

        var maxX = larguraJanela - botaoNao.offsetWidth;
        var maxY = alturaJanela - botaoNao.offsetHeight;

        var aleatorioX = Math.floor(Math.random() * maxX);
        var aleatorioY = Math.floor(Math.random() * maxY);

        botaoNao.style.left = aleatorioX + "px";
        botaoNao.style.top = aleatorioY + "px";
    }

    function mostrarNovaPagina() {
        document.getElementById("painel-principal").style.display = "none";
        document.getElementById("nova-pagina").style.display = "block";
    }
</script>

</body>
</html>
