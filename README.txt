# FasoServices — prototype MVP

## Tester
1. Décompressez `FasoServices_MVP.zip`.
2. Ouvrez `index.html` dans un navigateur pour tester l'interface.
3. Pour tester l'installation PWA, hébergez le dossier sur un hébergement HTTPS (par exemple Netlify), puis ouvrez le lien dans Chrome Android et choisissez « Installer l'application » / « Ajouter à l'écran d'accueil ».

## Fonctions incluses
- Recherche par texte et catégories.
- Fiches professionnelles.
- Liens d'appel et WhatsApp.
- Formulaire d'inscription avec consentement.
- File d'attente locale et validation manuelle de démonstration.

## Limites importantes
Ceci est un prototype local, pas encore une plateforme publique multi-utilisateur.
Les annonces sont conservées dans le stockage du navigateur de l'appareil. Elles ne sont pas envoyées à un administrateur et ne sont pas partagées entre téléphones.
L'espace de validation est une démonstration sans authentification : ne l'utilisez pas pour gérer de vraies données.
Avant le lancement public, il faudra connecter une base de données en ligne (par exemple Supabase), protéger l'administration par authentification, ajouter une politique de confidentialité, sécuriser les formulaires et tester les numéros/consentements.
Les tarifs, la disponibilité et l'identité des professionnels doivent être vérifiés par l'équipe FasoServices.
