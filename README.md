<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <title>Redirection Autonix...</title>
</head>
<body>
    <div style="text-align: center; margin-top: 50px; font-family: Arial, sans-serif;">
        <h2>Redirection en cours vers Autonix...</h2>
        <p>Si vous n'êtes pas redirigé automatiquement, vérifiez votre lien.</p>
    </div>

    <script>
        const currentUrl = window.location.href;
        const deepLinkUrl = currentUrl.replace('https://eyabouaziz-2000.github.io/index.html', 'autonix://set-password');
        window.location.href = deepLinkUrl;
    </script>
</body>
</html>
