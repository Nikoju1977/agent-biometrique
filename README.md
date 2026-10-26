# 🧬 Agent Biométrique

## Ce que fait l'application, en pratique

Cette interface propose de **démarrer ou arrêter une session d'analyse biométrique**, d'afficher des statistiques de session et de consulter une **note clinique de démonstration**. Elle sert à explorer la présentation d'indicateurs et de résultats d'IA dans un tableau de bord web, pas à produire des mesures médicales certifiées.

**Statut :** prototype de santé expérimental ; les interprétations doivent être vérifiées et ne doivent jamais être utilisées pour diagnostiquer ou traiter une personne.

**Studio Niko Design** — Agent IA d'analyse biométrique santé.

## ✨ Fonctionnalités
- Analyse biométrique multi-paramètres
- Suivi longitudinal des données santé
- Alertes et recommandations IA personnalisées

## 🛠 Stack
`HTML` · `Mistral AI` · `Chart.js` · `AES-256-GCM`

## 👤 Auteur
**Nicolas Julienne** — [Studio Niko Design](https://github.com/Nikoju1977) · Candidat BPI France
📧 nicolasjulienne.nj@gmail.com

---

## Utilisation, périmètre et maturité

**Thème :** HealthTech — expérimentation d'analyse biométrique.

Le dépôt contient une interface web (`index.html`) accompagnée d'une icône et d'un manifeste. Pour une inspection locale, servir la racine du dépôt avec `python3 -m http.server 8000`, puis ouvrir http://localhost:8000/. Les services d'IA ou ressources distantes peuvent nécessiter un accès réseau et une configuration propre à l'application.

**Limites :** projet exploratoire ; ni diagnostic ni interprétation clinique validée. Ne pas saisir de données de patients réels sans évaluation préalable de la confidentialité, de la sécurité et des flux réseau. Les capacités annoncées ci-dessus n'ont pas fait l'objet d'une validation médicale indépendante.

**État de validation :** documentation actualisée à partir de la structure du dépôt ; aucun test d'exécution, contrôle de sécurité ou audit réglementaire n'est revendiqué.

[Voir les autres projets Studio Niko Design](https://github.com/Nikoju1977).
