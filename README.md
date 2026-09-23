<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <title>Redirection Autonix...</title>
</head>
<body>
    <div style="text-align: center; margin-top: 50px; font-family: Arial, sans-serif;">
        <h2>Redirection en cours vers Autonix...</h2>
        <p>Si l'application ne s'ouvre pas automatiquement, vérifiez votre installation.</p>
    </div>

    <script>
        // Récupère l'URL complète avec le token d'accès
        const currentUrl = window.location.href;
        
        // Remplace l'adresse web par votre protocole mobile personnalisé
        const deepLinkUrl = currentUrl.replace('https://eyabouaziz-2000.github.io/index.html', 'autonix://set-password');
        
        // Redirige instantanément vers l'application
        window.location.href = deepLinkUrl;
    </script>
</body>
</html>
