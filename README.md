# Math avec Mohamed — V2 bilingue

Prototype web responsive en français et en arabe (RTL/LTR).

## Tester
Ouvrir `index.html` dans un navigateur. Pour tester le mode PWA/service worker, servir le dossier via localhost ou HTTPS :
`python -m http.server 8000`

## Fonctionnalités incluses
- Interface française/arabe avec bascule de langue.
- Accueil et choix des six niveaux.
- Espace élève : QCM, correction, explication bilingue et score de session.
- Espace professeur : formulaire d'ajout de questions avec énoncé et explication en français/arabe.
- Sauvegarde locale des questions dans le navigateur.
- Mise en page responsive et base PWA.

## Limites à traiter avant lancement public
Ce livrable reste un prototype front-end. Les comptes réels, authentification sécurisée, base de données cloud, rôles professeur/élève, classes, synchronisation multi-appareils, paiements et publication/domaine ne sont pas encore configurés. Les questions locales ne sont visibles que sur le même navigateur/appareil.


## Photo du professeur
La photo de la page d'accueil se trouve dans `assets/mohamed-profile.jpeg`. Pour la remplacer, gardez ce nom de fichier ou mettez à jour le chemin dans `index.html`.
