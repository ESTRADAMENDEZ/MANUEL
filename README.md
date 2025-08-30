<!DOCTYPE html>
<html>
<head>
  <style>
    body {
      font-family: Arial;
      background-color: #2abad3;
    }

    .menu {
      background-color: #333;
      overflow: hidden;
    }

    .menu a {
      float: left;
      color: white;
      padding: 14px 16px;
      text-decoration: none;
    }

    .menu a:hover {
      background-color: #575757;
    }

    .grid {
      display: grid;
      grid-template-columns: 2fr 1fr 1fr;
      gap: 100px;
      margin: 60px;
    }

    .celda {
      background-color: rgb(228, 174, 28);
      border: 1px solid #10dd3c;
      padding: 20px;
      text-align: center;
    }
  </style>
</head>
<body>

  <div class="menu">
    <a href="#">Inicio</a>
    <a href="#">Servicios</a>
    <a href="#">Contacto</a>
  </div>

  <div class="grid">
    <div class="celda">MANUEL MENDEZ: Distinguir el pensamiento educativo de lo cuantitativo</div>
    <div class="celda">Fila 1, Columna 1</div>
    <div class="celda">Fila 1, Columna 3</div>
   
  </div>
  <button onclick="saludar()">OTRO NIVEL</button>
<script>
  function saludar() {
    alert("¡Hola, Manuel!");
  }

</script>

</body>
</html>
