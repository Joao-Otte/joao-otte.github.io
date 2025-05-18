<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>João Otte</title>

    <style>
        body {
            background-color: rgb(0, 247, 255);
            font-family: Arial, sans-serif;
            padding: 20px;
        }

        h1 {
            color: rgb(241, 79, 15);
            font-size: 60px;
            text-align: center;
        }

        .superparagrafo {
            font-size: 20px;
        }

        .img-arredondada {
            border-radius: 15px;
        }

        ul li {
            margin-bottom: 10px;
        }

        a:hover {
            color: red;
        }
    </style>
</head>
<body>

    <h1>João Otte</h1>

    <p class="superparagrafo">
        Meu nome é João Guilherme Silva Otte da Silva, tenho 19 anos, moro em Porto Alegre, gosto de programação e esportes.
    </p>

    <ul> 
        <li>Vôlei</li>
        <li>Viajar</li>
        <li>Jogar Videogame</li>   
    </ul>
    
    <img class="img-arredondada" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ_-sB7F1FgJHbfL1MGhbXkM6wypcq0wYg2sg&s" alt="Imagem pessoal">

    <table border="2" cellpadding="6">
        <tr>
            <th>País</th>
            <th>Imagem</th>
        </tr>
        <tr>
            <td>Japão</td>
            <td><img src="https://www.moneytimes.com.br/uploads/2021/04/japao-3.jpg" alt="Japão" width="150"></td>
        </tr>
        <tr>
            <td>Canadá</td>
            <td><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRH-07QcX2Vx85TwkysHAPizXhN0ub5qXskaA&s" alt="Canadá" width="150"></td>
        </tr>
        <tr>
            <td>Itália</td>
            <td><img src="https://nexustraducoes.com/wp-content/uploads/2023/05/morar-na-italia-1.webp" alt="Itália" width="150"></td>
        </tr>
    </table>

    <p><a href="https://www.tecmundo.com.br" target="_blank">Visite o TecMundo</a></p>

    <button onclick="mostrarMensagem()">Clique para ver uma mensagem!</button>
    <p id="mensagem"></p>

    <script>
        function mostrarMensagem() {
            document.getElementById("mensagem").textContent = "Chegou ao fim, obrigado pela visita!";
        }
    </script>

</body>
</html>
