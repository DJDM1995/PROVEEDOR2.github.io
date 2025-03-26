<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página Protegida</title>
    <script>
        // Verifica si el usuario accedió correctamente
        if (sessionStorage.getItem("accesoPermitido") !== "true") {
            alert("⚠️ No tienes acceso a esta página.");
            window.location.href = "https://djdm1995.github.io/PROVEEDOR.githuh.io/"; // Regresa a la página de contraseña
        }
    </script>
</head>
<body>
    <h1>✅ ¡Bienvenido a la página protegida!</h1>
    <p>Solo puedes ver esto si ingresaste la contraseña correcta.</p>
</body>
</html>
