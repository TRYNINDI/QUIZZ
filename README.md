<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Quizz Futebol Brasileiro</title>
    <style>
        body {
            background-color: #000; /* fundo preto */
            color: #fff; /* letras brancas */
            font-family: Arial, sans-serif;
        }
        
        header {
            text-align: center;
            padding: 20px;
        }
        
        h1, h2 {
            color: #fff;
        }
        
        form {
            max-width: 600px;
            margin: 40px auto;
            padding: 20px;
            background-color: #333;
            border: 1px solid #444;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
        }
        
        section {
            margin-bottom: 20px;
        }
        
        input[type="radio"] {
            margin: 10px;
        }
        
        label {
            margin: 10px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Quizz Futebol Brasileiro</h1>
    </header>
    <form>
        <section>
            <h2>Pergunta 1: Qual é o time mais vezes campeão brasileiro?</h2>
            <input type="radio" id="palmeiras" name="pergunta1">
            <label for="palmeiras">Palmeiras</label>
            <input type="radio" id="santos" name="pergunta1">
            <label for="santos">Santos</label>
            <input type="radio" id="flamengo" name="pergunta1">
            <label for="flamengo">Flamengo</label>
        </section>
        <section>
            <h2>Pergunta 2: Quem é o maior artilheiro da seleção brasileira?</h2>
            <input type="radio" id="pele" name="pergunta2">
            <label for="pele">Pelé</label>
            <input type="radio" id="romario" name="pergunta2">
            <label for="romario">Romário</label>
            <input type="radio" id="ronaldo" name="pergunta2">
            <label for="ronaldo">Ronaldo</label>
        </section>
        <section>
            <h2>Pergunta 3: Qual é o estádio mais grande do Brasil?</h2>
            <input type="radio" id="maracana" name="pergunta3">
            <label for="maracana">Maracanã</label>
            <input type="radio" id="arena Corinthians" name="pergunta3">
            <label for="arena Corinthians">Arena Corinthians</label>
            <input type="radio" id="allianz Parque" name="pergunta3">
            <label for="allianz Parque">Allianz Parque</label>
        </section>
        <section>
            <h2>Pergunta 4: Quem é o treinador mais vezes campeão brasileiro?</h2>
            <input type="radio" id="luiz Felipe Scolari" name="pergunta4">
            <label for="luiz Felipe Scolari">Luiz Felipe Scolari</label>
            <input type="radio" id="carlos Alberto Parreira" name="pergunta4">
            <label for="carlos Alberto Parreira">Carlos Alberto Parreira</label>
            <input type="radio" id="tite" name="pergunta4">
            <label for="tite">Tite</label>
        </section>
        <section>
            <h2>Pergunta 5: Qual é o time que mais vezes foi vice-campeão brasileiro?</h2>
            <input type="radio" id="santos" name="pergunta5">
            <label for="santos">Santos</label>
            <input type="radio" id="flamengo" name="pergunta5">
            <label for="flamengo">Flamengo</label>
            <input type="radio" id="cruzeiro" name="pergunta5">
            <label for="cruzeiro">Cruzeiro</label
