<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Para minha princesa ❤️</title>

    <style>
        body {
            background-color: #ffe6f0;
            font-family: Arial, sans-serif;
            text-align: center;
            padding-top: 100px;
        }

        .caixa {
            background: white;
            padding: 40px;
            border-radius: 25px;
            max-width: 500px;
            margin: auto;
            box-shadow: 0 5px 20px #0003;
        }

        h1 {
            color: #e91e63;
        }

        button {
            padding: 15px 30px;
            margin: 10px;
            border: none;
            border-radius: 15px;
            font-size: 18px;
            cursor: pointer;
        }

        #sim {
            background: #ff4f81;
            color: white;
        }

        #nao {
            background: #ddd;
        }

        #resposta {
            margin-top: 25px;
            font-size: 18px;
            line-height: 1.5;
        }

        .gato {
            font-family: monospace;
            margin-top: 25px;
        }
    </style>
</head>

<body>

<div class="caixa">

    <h1>💌 Uma perguntinha...</h1>

    <h2>Você sabia que eu te amo?</h2>

    <button id="sim">SIM ❤️</button>
    <button id="nao">NÃO 😳</button>

    <div id="resposta"></div>

    <div class="gato">
        /\_/\\
       ( o.o )
        > ^ <
       /|   |\\
      (_|   |_)
    </div>

</div>

<script>

document.getElementById("sim").onclick = function() {

    document.getElementById("resposta").innerHTML =
    "SIMMMMMMMMMMMMMMMMMMMMMMMMMMMMM ❤️<br>" +
    "MINHA PRINCESA, EU TE AMO MUITÃOOOOOOOOOOOO! " +
    "VOCÊ É MEU ORGULHO E MINHA FELICIDADE. <3";

};

document.getElementById("nao").onclick = function() {

    document.getElementById("resposta").innerHTML =
    "COMO NÃO??? 😭❤️<br>" +
    "EU TE AMOOOOOOOO MUITOOOOOOOOOOOO! " +
    "VOCÊ É MINHA PRINCESA, MEU AMOR, MINHA FELICIDADE E MEU MAIOR ORGULHO. <3";

};

</script>

</body>
</html>
