<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Seja Bem-Vindo</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f4f4f4;
            font-family: Arial, sans-serif;
        }
        h1 {
            font-size: 3rem;
            color: #333;
            animation: fadeIn 2s ease-in-out, fadeOut 2s ease-in-out 3s forwards;
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        @keyframes fadeOut {
            from { opacity: 1; }
            to { opacity: 0; }
        }
    </style>
    <script>
        setTimeout(() => {
            window.location.href = 'site.html';
        }, 5000); // Redireciona após 5 segundos
    </script>
</head>
<body>
    <h1>SEJA BEM-VINDO</h1>
</body>
</html>
