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
        // Récupérer toute l'URL actuelle (avec le token d'invitation de Supabase après le # ou ?)
        const currentUrl = window.location.href;
        
        // Option A : Si vous voulez transformer l'URL web en schéma personnalisé pour l'app mobile
        // (Exemple : transformer https://votre-site.com/#access_token=... en autonix://set-password#access_token=...)
        const deepLinkUrl = currentUrl.replace('https://votre-site.com', 'autonix://set-password');

        // Tentative d'ouverture de l'application mobile
        window.location.href = deepLinkUrl;

        // Option B (Alternative) : Afficher le lien ou le token si l'utilisateur est sur PC
        // pour qu'il puisse le copier-coller dans l'application mobile.
    </script>
</body>
</html>