# AGENTS.md — Studio Niko / Modern Web Guidance

Référence officielle : https://github.com/GoogleChrome/modern-web-guidance
Pour un changement de code frontend, sélectionner un guide réellement pertinent à partir de `npx modern-web-guidance@latest search "accessible responsive forms"`, puis utiliser `retrieve` avec l'identifiant obtenu. La CLI s'exécute côté développeur Node.js, jamais dans le navigateur mobile.

Rechercher la simplicité, l'HTML sémantique, les formulaires accessibles, le zoom mobile, la compatibilité Safari iOS/Chrome/Firefox, la performance et la dégradation progressive. Conserver les fonctionnalités documentées.

## Priorité propre à ce dépôt

Tableau de bord biométrique expérimental. Séparer indicateurs de démonstration et données réellement mesurées, protéger les données sensibles et ne pas affirmer de validité diagnostique.

## Publication et véracité

- Ne jamais exposer de secrets, identifiants de patients ni données privées dans du code public.
- Ne pas lancer de campagne de tests sans demande explicite. Ne jamais afficher « test réussi » sans preuve.
- Dire précisément : lu, modifié dans GitHub, publié sur l'hébergement, vérifié sur appareil.
