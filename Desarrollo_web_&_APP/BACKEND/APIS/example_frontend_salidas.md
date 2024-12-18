<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registro de Usuario</title>
</head>
<body>
    <h1>Registrar Usuario</h1>
    <form action="http://localhost:5000/registro" method="POST">
        <label for="nombre">Nombre:</label>
        <input type="text" id="nombre" name="nombre" required>
        <br><br>
        <label for="contraseña">Contraseña:</label>
        <input type="password" id="contraseña" name="contraseña" required>
        <br><br>
        <button type="submit">Registrar</button>
    </form>
</body>
</html>

//este html es un ejemplo de donde se tienen que hacer las peticiones, como por ejemplo el nombre y la contraseña, 
