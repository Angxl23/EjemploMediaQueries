<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ejemplo Media Queries</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      text-align: center;
      color: white;
    }

    /* Estilo base (escritorio) */
    body {
      background-color: steelblue;
      font-size: 24px;
    }

    /* Tablet (481px - 1024px) */
    @media (min-width: 481px) and (max-width: 1024px) {
      body {
        background-color: seagreen;
        font-size: 20px;
      }
    }

    /* Móvil (max 480px) */
    @media (max-width: 480px) {
      body {
        background-color: orange;
        font-size: 16px;
      }
    }
  </style>
</head>
<body>
  <h1>Diseño Responsivo con Media Queries</h1>
  <p>Cambia el tamaño de la ventana o abre en otro dispositivo para ver el cambio de color y tamaño de texto.</p>
</body>
</html>
