<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calculadora Geométrica</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <main>
        <div class="container2">
            <p class="para">O objetivo dessa calculadora é fazer cálculos com base na quantidade de lados dados pelo usuário. Podendo calcular formas geométricas de 3-10 lados. </p>
        </div>
        <div class="container">
          <div class="title"> Calculadora Geométrica </div>
          <div class="input">
              <label>Quantidade de lados:</label>
              <input type="number" id='qtd'>
          </div>

          <button id='calcular'>Calcular</button>
 
          <div class="result" id='resultado'></div>
        </div>
      </main>
    <script src="func.js"></script>
</body>
</html>
