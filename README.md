<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Redirigiendo...</title>
    <!-- Redirección directa por Meta Tag (La más compatible) -->
    <meta http-equiv="refresh" content="0;url=https://youtube.com">
</head>
<body>
    <div style="text-align: center; margin-top: 50px; font-family: sans-serif;">
        <p>Redirigiendo al vídeo...</p>
        <!-- Botón de auxilio por si el navegador bloquea la acción automatizada -->
        <a id="enlace" href="https://youtube.com" style="color: #007bff; text-decoration: none; font-weight: bold;">
            Si no redirige automáticamente, haz clic aquí
        </a>
    </div>

    <script>
        // Truco definitivo: Simular un clic real del usuario en el enlace de arriba
        // Esto se salta la seguridad antipopups del navegador
        document.getElementById('enlace').click();
    </script>
</head>
<body>
</body>
</html>

