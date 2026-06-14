# DTLteach

DTLteach est un guide Windows 11 simple et autonome, destiné aux débutants, aux personnes âgées et à toute personne qui souhaite une introduction calme aux usages quotidiens de l'ordinateur.

Le projet est une page HTML en français. Elle explique les concepts courants de Windows 11 avec des sections courtes, un vocabulaire simple, une barre de navigation fixe et une capture locale du menu Démarrer.

## Contenu

Le guide couvre :

- le menu Démarrer de Windows 11 ;
- les six raccourcis utiles de la colonne gauche du menu Démarrer ;
- l'agrandissement du texte et de l'affichage ;
- le Bureau Windows ;
- les boutons de fenêtre ;
- l'Explorateur de fichiers ;
- la navigation Internet avec Google Chrome ;
- les bases de l'e-mail ;
- les clés USB ;
- la connexion Wi-Fi ;
- les programmes essentiels ;
- les habitudes de sécurité de base.

## Fichiers

- `DTLteach.html` : guide complet avec HTML et CSS.
- `menu_Windows_11.png` : capture utilisée dans la section sur le menu Démarrer.

## Utilisation

Ouvrir `DTLteach.html` dans un navigateur web.

Aucune installation, aucun serveur, aucune étape de build et aucune dépendance externe ne sont nécessaires. La page fonctionne comme un fichier statique local tant que `menu_Windows_11.png` reste dans le même dossier que le fichier HTML.

## Modification

La page est volontairement légère :

- les liens de navigation sont définis dans la section `.sidebar` ;
- chaque leçon est une balise `<section>` avec son propre `id` ;
- le style visuel est intégré dans le bloc `<style>` au début de `DTLteach.html`.

Pour ajouter un chapitre, ajouter un nouveau lien dans la barre latérale et une section correspondante avec le même identifiant d'ancre.

## Public

Ce guide est conçu pour des ateliers pratiques de culture numérique où les participants découvrent parfois Windows pour la première fois. Le ton privilégie la confiance, la clarté et l'apprentissage étape par étape plutôt que le détail technique.

## Mise à jour - 14 juin 2026

Le dépôt contient maintenant plusieurs supports HTML complémentaires.

Fichiers importants :

- `DTLteach.html` : page principale du guide Windows 11.
- `DTLteach_Fr.html` : version française séparée du même support pédagogique.
- `programmes_presents.html` : inventaire pédagogique des programmes et outils fournis avec Windows 11.
- `menu_Windows_11.png` : capture utilisée dans la section sur le menu Démarrer.

Le guide couvre toujours les bases de Windows 11, tandis que l'inventaire des programmes ajoute une vue plus large des paramètres, de la sécurité, des outils d'administration, de la communication, de l'accessibilité et des utilitaires Microsoft.
